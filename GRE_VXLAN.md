## VXLAN

### Topology

<src img="https://github.com/lean15998/Vitualization/blob/main/images/11.01.PNG">
  
### Cấu hình tại HOST 1

 - Tạo Vswitch
  
 <src img="https://github.com/lean15998/Vitualization/blob/main/images/11.02.PNG">
    
 - Add port ens38 vào vswitch ovs2
  
 <src img="https://github.com/lean15998/Vitualization/blob/main/images/11.03.PNG">
      
 - Set IP cho 2 vswitch
  
 <src img="https://github.com/lean15998/Vitualization/blob/main/images/11.04.PNG">
        
 - Add port VXLAN tunnel interface cho vswitch ovs2
   
 <src img="https://github.com/lean15998/Vitualization/blob/main/images/11.05.PNG">
          
 - Xem thông số cấu hình
  
 - Tạo libvirt network ứng với vswitch ovs1 để kết nối vào máy VM
 
 - Add interface vào trong VM
  
 - Set IP cho VM1
  
 - Kiểm tra kết nối với vswitch ovsbr1
  
  
  
### Cấu hình tại HOST 2
  

 - Tạo Vswitch
  
 - Add port ens38 vào vswitch ovs2
  
 - Set IP cho 2 vswitch
  
 - Add port VXLAN tunnel interface cho vswitch ovs2
   
 - Xem thông số cấu hình
  
 - Tạo libvirt network ứng với vswitch ovs1 để kết nối vào máy VM
 
 - Add interface vào trong VM
  
 - Set IP cho VM2
  
 - Kiểm tra kết nối với vswitch ovsbr1
  
  - Kiểm tra kết nối với VM1
  

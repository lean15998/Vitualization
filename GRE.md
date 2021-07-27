## GRE

### Topology

<img src="https://github.com/lean15998/Vitualization/blob/main/images/11.01.PNG">
  
### Cấu hình tại HOST 1

 - Tạo Vswitch
  
<img src="https://github.com/lean15998/Vitualization/blob/main/images/11.02.PNG">
    
 - Add port ens38 vào vswitch ovs2
  
<img src="https://github.com/lean15998/Vitualization/blob/main/images/11.03.PNG">
      
 - Set IP cho 2 vswitch
  
<img src="https://github.com/lean15998/Vitualization/blob/main/images/11.04.PNG">
        
 - Add port VXLAN tunnel interface cho vswitch ovs2
   
<img src="https://github.com/lean15998/Vitualization/blob/main/images/11.05.PNG">
          
 - Xem thông số cấu hình

<img src="https://github.com/lean15998/Vitualization/blob/main/images/11.06.PNG">
<img src="https://github.com/lean15998/Vitualization/blob/main/images/11.07.PNG">
  
 - Tạo libvirt network ứng với vswitch ovs1 để kết nối vào máy VM
 
 <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.08.PNG">
 <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.09.PNG">
 <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.10.PNG">
 
 - Add interface vào trong VM
  
  <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.11.PNG">
  
 - Set IP cho VM1
  
   <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.12.PNG">
   
 - Kiểm tra kết nối với vswitch ovsbr1
  
  <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.13.PNG">

  
### Cấu hình tại HOST 2
  

 - Tạo Vswitch
  
<img src="https://github.com/lean15998/Vitualization/blob/main/images/11.14.PNG">
   
 - Add port ens38 vào vswitch ovs2
   
<img src="https://github.com/lean15998/Vitualization/blob/main/images/11.15.PNG">
   
 - Set IP cho 2 vswitch

 <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.16.PNG">
  
 - Add port VXLAN tunnel interface cho vswitch ovs2
   
  <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.17.PNG">
  
 - Xem thông số cấu hình

 <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.18.PNG">
  <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.19.PNG">
  
 - Tạo libvirt network ứng với vswitch ovs1 để kết nối vào máy VM

 <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.20.PNG">
  <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.21.PNG">
 
 - Add interface vào trong VM

 <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.22.PNG">
  
 - Set IP cho VM2
  
  <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.23.PNG">
  
 - Kiểm tra kết nối với vswitch ovsbr1
  
   <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.24.PNG">
  
 - Kiểm tra kết nối với VM1
  
 <img src="https://github.com/lean15998/Vitualization/blob/main/images/11.25.PNG">

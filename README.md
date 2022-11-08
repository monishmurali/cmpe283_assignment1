[1] I did it by myself.


[2] steps followed

  1. I have retrieved .c file and makefile from the canvas.
  2. enabled google cloud VM and also ennabled nested virtualization.
  3. updated the .c file to display vmx configurationfor process based, entry and exit MSRs.
  4. Based on the Info from SDM added capability structs and made calls to rdmsr and report_capability in .c file.
  5. Executed the make Command.
  6. Executed sudo dmesg command to verify vmx capabilities for MSRs are displayed.
  7. commited to github.
  
  
  created directory and .c file.
  <img width="326" alt="cmpe_directory" src="https://user-images.githubusercontent.com/59603371/200457621-a50a00f7-436d-4433-9451-4fa86380ce0f.PNG">

  installed linux headers.
  <img width="836" alt="cmpe_make" src="https://user-images.githubusercontent.com/59603371/200457501-cb724dc1-d07c-46b5-9806-107382690a71.PNG">


   displayed vmx capabilities using dmesg command.
<img width="726" alt="cmpe_output" src="https://user-images.githubusercontent.com/59603371/200456884-9e04cb2b-17da-474b-acc7-e2fa6b0f4aa3.PNG">

  <img width="472" alt="cmpe_output2" src="https://user-images.githubusercontent.com/59603371/200456975-417091e8-f22d-4a6f-9792-b0ebcb5d59fe.PNG">

  


 


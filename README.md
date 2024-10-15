# eUVM_INTERNSHIP_COVERIFY
https://www.edaplayground.com/x/mx9_
Steps to run eUVM
```
  cd ~/dev/goossens-book-ip-projects/2022.1/chapter_2/sim_vl/
   make clean
   make link_verilator
   make my_adder_ip
   make run
```
![image](https://github.com/user-attachments/assets/5f8910cb-46c8-415b-b91f-4c965ef0c26c)

After running make run
![image](https://github.com/user-attachments/assets/209cc77e-7cb8-434b-a39a-4e9941ee4492)

To run waveforms
```
gtkwave my_adder_ip.vcd
```
![image](https://github.com/user-attachments/assets/820d4e68-b067-4a83-b3a1-10d2df74377a)
```
cd ../testbench_vl
ls -ltr
```
![image](https://github.com/user-attachments/assets/3e6f6070-02e7-49c5-bc0f-b283b2c44c82)
```
 nano axi4_lite.d
```
![image](https://github.com/user-attachments/assets/e166b607-c210-4d8a-83a9-f8e1aec9583e)

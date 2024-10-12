# eUVM_INTERNSHIP_COVERIFY

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

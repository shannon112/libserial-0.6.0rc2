# libserial
This library can be used to access the serial ports on POSIX  
systems. You will need the latest gcc release (anything after gcc-3.2  
should work) to compile libserial.  
  
When you have installed the above tools, run the following commands:  
```
./configure 
make
make install
```
Enjoy,  
CrayzeeWulf  
  
### Quickly start
```
cd /tmp
git clone https://github.com/shannon112/libserial-0.6.0rc2.git
cd libserial-0.6.0rc2
./configure
make
sudo make install
sudo ldconfig
```
What is ldconfig ?  
ldconfig is a program that is used to maintain the shared library cache. This cache is typically stored in the file /etc/ld.so.cache and is used by the system to map a shared library name to the location of the corresponding shared library file

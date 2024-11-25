1.  Telnet class are called to implementdifferent functions in pythons telnetlib module. Discuss
    the usage implementation of the following as used in python;

         i. Telent.close()
         ii. From telnetlib import Telnet
         iii. Telnet.read until(expected, timeout=None)

2.  A function is a group of statements that together perform a task. Describe any three
    benefits of functions in a computer program.

3.  A variable is a name given to a memory location. Describe four rules for creating
    variables.

4.  An IP address is a unique address that identifies a device on the internet or a local network.
    Describe `four` major differences between IPv4 and IPv6 addresses.

5.  You are the network administrator for a medium-sized company,and you need to select and
    configure network service applications to meet specific organizational needs. Describe the
    following network services and application protocols:

         i. DHCP
         ii. SSH
         iii. DNS

6.  Discuss `two` major limitations of LAN that led to adoption of VLANs.

7.  The continued growth of IP networks in general has resulted in an ever increasing pressure
    on the IPv4 address space,and the need for a way to prolong the depletion until long term
    solutions are found.

            i. Discuss five advantages ofnetworkaddress translation.
            ii. Discuss five forms of Network Address Translation implementation

8.  Authentication, Authorization and Accounting defines a security architecture that is
    comprised of three functions. Describe three AAA schemes supported when configuring
    VRP.

9.  IPv6 is the most recent version of the Internet Protocol (IP).What is the most abbreviated
    form of the following IPv6 addresses:

    i. `2001:0DB8:0000:0000:0008:0800:200C:417A`

    ii. `2001:0DB8:0000:0000:FB00:1400:5000:45FF`

    iii. `2001:0DB8:0000:1234:FB00:0000:5000:45FF`

    iv. `2001:0DB8:0000:0000:032A:0000:0000:2D70`

    v. `FDS9:8F911:F52D:0000:0001:0000:0000:0001`

10. Almost everything in Python is an object, with its properties and methods. Create a class
    named User. Make two methods:

            i. Login -Takes password as a parameter and prints "user Logged in successfully."

            ii. Logout - It will print "user Logged out successfully."

11. A network device functions as a Telnet server, and the Python telnetlib needs to be used as a
    Telnet client to login to the device. Elaborate the following python module.

    ```
    import telnetlib
    host ='192.168.10.10'
    password ='Huawei@123'
    tn =telnetlib.Telnet(host)
    tn.read_until(b'Password:')
    tn.write(password.encode('asci') + b"\n")
    print (tn.read_until(b'<Huawei>').decode('ascir'))
    tn.close()
    ```

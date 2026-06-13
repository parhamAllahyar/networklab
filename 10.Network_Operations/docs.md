```
                Internet
                   |
                ISP Router
                   |
                 Edge
                Router
                   |
               Firewall
              /        \
           DMZ        Core
            |           |
        Web Server   Core1-----Core2
                         |       |
                 ---------       ----------
                 |                        |
           Distribution1            Distribution2
            |       |                |        |
        Access1  Access2         Access3   Access4
          |         |               |         |
        Users    Servers         Users      VoIP

```
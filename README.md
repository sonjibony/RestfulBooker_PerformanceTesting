# Restful_Booker_Performance_Testing

## Prerequisites
- JMeter 5.6, Java 8 and above are supported.
- Memory 16GB RAM is a good value.
- Multicore cpus with 4 or more cores are suggested to use.

## Technology used:
- Apache JMeter
  
## Test execution (from the Terminal)
- JMeter should be initialized in non-GUI mode.
- Make a report folder in the bin folder.
- Run Command in jmeter\bin folder.
  
- Jtl file Command:
```console
jmeter -n -t heroku_T100.jmx -l report\heroku_T100.jtl
```
Keep increasing Threads by keeping Ramp-up Same.

- Html Report Install Command:
```console
jmeter -g report\heroku_T100.jtl -o report\heroku_T100.html
```
## Report Summary:
![Report Summary](https://github.com/user-attachments/assets/d3c4443e-eab2-4bec-8657-af20b686e8b5)

![Newman Report Summary](https://github.com/user-attachments/assets/1c263dd2-0771-4545-abd8-ff6ad0d6a72f)

![Newman Report Summary](https://github.com/user-attachments/assets/0ec4b04d-664d-4dc9-ae96-8838a9fd30b0)




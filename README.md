- Download jmeter from brow 
- 1. download chrome extention name: BlazeMeter , The Continuous Testing Platform

![Screenshot 2020-11-18 at 3 32 32 PM](https://user-images.githubusercontent.com/58136550/99512191-64164d00-29b3-11eb-8a7a-c8b4226ac80c.png)

- 2. record page 
- 3. save .jmx file 
- 4. open it form jmeter 
- 5. write some assertion 
- 6. added some listener 
- 7. test & clen 

for report generate 
```code
 jmeter -n -t whereis.jmx -l whereloadtest.csv -e -o whereHTMLreportfolder
```

- finish 
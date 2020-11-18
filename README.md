- Download jmeter from brow 
- 1. download chrome extention name: BlazeMeter , The Continuous Testing Platform

![Screenshot 2020-11-18 at 3 32 32 PM](https://user-images.githubusercontent.com/58136550/99512191-64164d00-29b3-11eb-8a7a-c8b4226ac80c.png)

- 2. record page 
- 3. save .jmx file 
- 4. open it form jmeter 

<img width="1280" alt="Screenshot 2020-11-18 at 3 42 28 PM" src="https://user-images.githubusercontent.com/58136550/99513598-02ef7900-29b5-11eb-8791-c16c412e9f81.png">

- 5. write some assertion 

<img width="1280" alt="Screenshot 2020-11-18 at 3 42 17 PM" src="https://user-images.githubusercontent.com/58136550/99513531-f3703000-29b4-11eb-94c7-d46ec31b8069.png">


- 6. added some listener 
<img width="1280" alt="Screenshot 2020-11-18 at 3 42 10 PM" src="https://user-images.githubusercontent.com/58136550/99513495-e5baaa80-29b4-11eb-8648-e5ab5b7a1906.png">

- 7. test & clen 

for report generate 
```code
 jmeter -n -t whereis.jmx -l whereloadtest.csv -e -o whereHTMLreportfolder
```

- finish 

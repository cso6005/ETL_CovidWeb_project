# π· ETL_Covid-19 Web

 <span style="color:gray">*__Project Summary__*</span>

**βοΈ νλ‘μ νΈ λͺ**

ETLμ μ μ©ν covid-19 νν© μλ΄ μΉ μ νλ¦¬μΌμ΄μ

**βοΈ νλ‘μ νΈ κΈ°κ°**

2022.09.14 ~ 2022.09.16

**βοΈ νλ‘μ νΈ νν**

4μΈ ν νλ‘μ νΈ


## 01. νλ‘μ νΈ κΈ°ν λ° μ€κ³

**βοΈ μ£Όμ μλΉμ€**

  :chart_with_upwards_trend: μμ 10κ°κ΅­ μ½λ‘λ νμ§μ μ νν© μλ΄ μλΉμ€

  :bar_chart:  μμ 10κ°κ΅­ μ½λ‘λ νμ§μ λλΉ μ¬λ§λ₯  μλ΄ μλΉμ€

  :mag_right:  νΉμ  κ΅­κ° μ½λ‘λ νν© κ²μ μλΉμ€



**βοΈ κ°λ° μ€ν λ° μ¬μ© TOOL**

- **OS**

<img src="https://img.shields.io/badge/Windows-0078D6?style=flat&logo=Windows&logoColor=white">

- **Back**

<img src="https://img.shields.io/badge/Flask-000000?style=flat&logo=Flask&logoColor=white"> <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white">

- **Front**

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white"> <img src="https://img.shields.io/badge/HTML-E34F26?style=flat&logo=HTML5&logoColor=white">

- **DB**

<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white"> 

- **DATA ETL pipline**

<img src="https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white"> <img src="https://img.shields.io/badge/PYMYSQL-4479A1?style=flat&logo=p&logoColor=white"> <img src="https://img.shields.io/badge/sqlalchemy-CC2927?style=flat&logo=p&logoColor=white">


- **IDE**

<img src="https://img.shields.io/badge/VSC-007ACC?style=flat&logo=VisualStudioCode&logoColor=white"> 


- **νλ‘μ νΈ κ΄λ¦¬**

<img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=Notion&logoColor=white"> <img src="https://img.shields.io/badge/Slack-4A154B?style=flat&logo=Slack&logoColor=white">


## 02. νλ‘μ νΈ μν λ΄μ©

**βοΈ κ°λ° λ° κΈ°μ  κ΅¬ν κ²°κ³Ό**
- **BACK**
    - `Flask` κΈ°λ°μ μΉ μ νλ¦¬μΌμ΄μ κ΅¬ν
    - render_template μΌλ‘ `HTML λλλ§`
    - λ°μ΄ν° κ΄λ¦¬ DB `Mysql`
    - `pymysql` μ μ΄μ©νμ¬, db μ°λ λ° λ°μ΄ν° read
    - Front μ `JSON` ν¬λ§· λ°μ΄ν° ν΅μ 

- **FRONT**
    - `goole.chart` API μ΄μ©νμ¬, GEO chart, BAR chart, PIE chart, table κ΅¬ν
    - μλΉμ€ κΈ°λ₯μ μ ν©ν `HTML`, `JavaScript` μ½λ κ΅¬ν

- **DATA pipline**
    - `ETL` νμ΄νλΌμΈ μ μ©
    - Extract_df
        - COVID-19 Data Repository open data API μμ λ°μ΄ν° get ν, csv νμΌλ‘ μΆμΆ
    - Transform
        - `pandas` λ₯Ό μ΄μ©νμ¬ λ°μ΄ν° μ μ²λ¦¬
    - Load
        - `sqlalchemy`, `pymysql` μ μ΄μ©νμ¬, db μ°λ ν data insert


**βοΈ ννμ΄μ§**

- λ©μΈνμ΄μ§

![11](https://user-images.githubusercontent.com/66711073/218301040-a31649f9-3810-469e-95e3-70617d7dc7e8.png)

- μμ 10κ°κ΅­ μ½λ‘λ νμ§μ μ νν© μ°¨νΈ

![22](https://user-images.githubusercontent.com/66711073/218301041-61ff3a3c-3f20-4abd-ab54-b056ccd07611.png)

- μμ 10κ°κ΅­ μ½λ‘λ νμ§μ λλΉ μ¬λ§λ₯  μ°¨νΈ

![33](https://user-images.githubusercontent.com/66711073/218301043-8f3b88a0-597e-4762-a687-3cd9042621e8.png)

- νΉμ  κ΅­κ° μ½λ‘λ νν© κ²μ

![44](https://user-images.githubusercontent.com/66711073/218301036-62b7e97a-9f0c-4b7d-85d1-a400c68028ce.png)


-----

β¬οΈβ¬οΈβ¬οΈ ***λ°μ΄ν° API***
https://github.com/CSSEGISandData/COVID-19

β¬οΈβ¬οΈβ¬οΈ ***μ°Έκ³ μ¬μ΄νΈ μ£Όμ***
https://medium.com/analytics-vidhya/building-a-etl-pipeline-226656a22f6d


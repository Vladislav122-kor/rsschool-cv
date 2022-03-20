# Korolyov Vladislav



### About myself



---



After graduation from the university I got a job as an Assistant of small company. Now I have been working here for 2 years. But now I realise that this job and in general this spheare is not the thing I’d like to do. I become interested in IT-sphere and started with learning of Java Script on YouTube. It was a little bit difficult and I decided to take a course.



**My personal goal** is to become a _full-fledged frontend developer_.



**My strengths**:


- perseverance;

- purposefulness;

- desire to learn and develop;

- memorizing a large flow of information.



### Skills



---



I have basic skills of:


- HTML;

- CSS;

- JS.



**Example**:



```

<html>
<head>
  <style>
    table {
      border-collapse: collapse;
    }

    td,
    th {
      border: 1px solid black;
      padding: 3px;
      text-align: center;
    }

    th {
      font-weight: bold;
      background-color: #E6E6E6;
    }
  </style>
</head>
<body>
  <div id="calendar"></div>
  <script>
    function createCalendar(elem, year, month) {
      let count = 0;
      let date = new Date(year, month-1)
      let d = date.getDate();
      let dateDay = date.getDay() - 1;

      if (dateDay < 0) {
        dateDay = 6;
      }
      
      const days = ["пн", "вт", "ср", "чт", "пт", "сб", "вс"];

      let table = document.createElement("table");
      calendar.append(table);

      for (let i = 0; i < days.length; i++) {
        let th = document.createElement("th");
        th.innerHTML = days[i];
        table.append(th);
      }

      for (let i = 0; i < 5; i++) {
        var tr = document.createElement("tr");
        table.append(tr);
        for (let y = 0; y < days.length; y++) {
          var td = document.createElement("td");
          if (count < dateDay) {
            td.innerHTML = "";
            tr.append(td);
            count += 1;
          }
          else if (count >= dateDay && (date.getMonth() + 1) === month) {
            td.innerHTML = d;
            tr.append(td);
            d += 1;
            date.setDate((date.getDate() + 1));
          } else {
            td.innerHTML = "";
            tr.append(td);
          }
        }
        
      }
      document.write(days[dateDay]);
    }
    createCalendar(calendar, 2021, 5);
  </script>
</body>
</html>
```



### Education



---



- 2016 Linguistic college;

- 2020 International university MITSO.



### English



---



**B2**



##### _Contacts:_



___



- Phone: **+375 29 635 28 43**;
- E-mail: __vladislav.korolyov1996@gmail.com__;

- GitHub: **[link][1]**.


[1]: https://github.com/Vladislav122-kor
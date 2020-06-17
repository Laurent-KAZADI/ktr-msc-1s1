# ktr-msc-1s1
MSC Pro Epitech
●1212 silver badges●1010 bronze badges edited
Oct 18 '18 at 11:25

M.A.K. Ripon
1,304●11 gold badge●2020 silver badges●3636 bronze badges
up vote
6
down vote
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=ISO-8859-1">
        <title>Insert title here</title>
    </head>
    <body>
        <table id="myTable" cellpadding="2" cellspacing="2" border="1" onclick="tester()"></table>
        <script>
            var student;
            for (var j = 0; j < 10; j++) {
                student = {
                    name: "Name" + j,
                    rank: "Rank" + j,
                    stuclass: "Class" + j,
                };
                var table = document.getElementById("myTable");
                var row = table.insertRow(j);
                var cell1 = row.insertCell(0);
                var cell2 = row.insertCell(1);
                var cell3 = row.insertCell(2);

                cell1.innerHTML = student.name,
                cell2.innerHTML = student.rank,
                cell3.innerHTML = student.stuclass;
            }
        </script>
    </body>
</html>

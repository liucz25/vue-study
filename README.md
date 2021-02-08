# vue-study

vue 组件学习

想做一个组件，根据restful 返回的json 动态生成表格

json：
     data:{
   
        tableInfr:{TableName:'table',
                    tableMethd:'post'},

        
       tableData: [{
            date: '2016-05-02',
            name: '王小虎',
            address: '上海市普陀区金沙江路 1518 弄'
          }, {
            date: '2016-05-04',
            name: '王小虎',
            address: '上海市普陀区金沙江路 1517 弄'
          }, {
            date: '2016-05-01',
            name: '王小虎',
            address: '上海市普陀区金沙江路 1519 弄'
          }, {
            date: '2016-05-03',
            name: '王小虎',
            address: '上海市普陀区金沙江路 1516 弄'
          }],
        }
        }
        
        
        
        
   表格：
   <table><thead><th>date</th><th>name</th><th>address</th></thead> <tbody><tr><td>2016-05-02</td><td>王小虎</td><td>上海市普陀区金沙江路 1518 弄</td></tr><tr><td>2016-05-04</td><td>王小虎</td><td>上海市普陀区金沙江路 1517 弄</td></tr><tr><td>2016-05-01</td><td>王小虎</td><td>上海市普陀区金沙江路 1519 弄</td></tr><tr><td>2016-05-03</td><td>王小虎</td><td>上海市普陀区金沙江路 1516 弄</td></tr></tbody></table>
        
        
        
        
        

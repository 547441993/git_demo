<html>
<head>
<style>
body {
  text-align:center;
}
</style>
<script type="text/javascript">
functionn MyAutoRun()
{
var comparevalue="1, /MxML[1]/trades[1]/trade[1]/tradeHeader[1]/tradeUserDefinedFields[1]/userDefinedField[23]/fieldValue[1]/text()[1] ,'MX_MLS_DEVsdsadsa@sc.com','MX_MLS_DEV@sc.com',2, /MxML[1]/trades[1]/trade[1]/tradeHeader[1]/tradeUserDefinedFields[1]/userDefinedField[24]/fieldValue[1]/text()[1] ,'MX_MLS_DEVsdasdfa@sc.com','MX_MLS_DEV@sc.com'".split(",");

var tb=document.getElementById("MsoNormalTable");

document.write("<div class=‘WordSection1’><table class=‘MsoNormalTable’ border=‘0’ cellspacing=‘0’ cellpadding=‘0’ width=‘100%’style=‘width: 100.0%; background: whitesmoke; border-collapse: collapse’>"+"<tr>");
document.write("<th>Expect_Path</th>"+"<th>Expect_Data</th>"+"<th>Real_Data</th></tr>");

var a=0;
var b=0;
var diffLength=alert(count(comparevalue));
document.write("<tr>");
while(a<diffLength)
{
   var td0=tb.rows[a].cells[0];
   var td1=tb.rows[a].cells[1];
   var td2=tb.rows[a].cells[2];
   document.write("<td>"+1+"</td>");	
   document.write("<td>"+2+"</td>");
   document.write("<td>"+3+"</td>");
   a++;
}
document.write("</tr></table></div>");
},


function count(o){

   var t=typeof o;
   if(t=="string"){
      return o.length;
   }else if(t=="object"){
      var n=0;
      for(var i in o){
         n++;
      }
      return n;
     }
     return false;
};


</script>
</head>
<body onLoad="MyAutoRun()">
<p>1</p>
</body>
</html>

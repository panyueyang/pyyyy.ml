# 小潘学习--加油
<title>小潘学习--加油</title>
<style>
  input{                 border: 1px solid #ccc;                 padding: 7px 0px;                 border-radius: 3px;                 padding-left:5px;                 -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075);                 box-shadow: inset 0 1px 1px rgba(0,0,0,.075);                 -webkit-transition: border-color ease-in-out .15s,-webkit-box-shadow ease-in-out .15s;                 -o-transition: border-color ease-in-out .15s,box-shadow ease-in-out .15s;                 transition: border-color ease-in-out .15s,box-shadow ease-in-out .15s             }             input:focus{                     border-color: #66afe9;                     outline: 0;                     -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075),0 0 8px rgba(102,175,233,.6);                     box-shadow: inset 0 1px 1px rgba(0,0,0,.075),0 0 8px rgba(102,175,233,.6)             }
button{                 border: 1px solid #ccc;                 padding: 7px 0px;                 border-radius: 3px;                 padding-left:5px;                 -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075);                 box-shadow: inset 0 1px 1px rgba(0,0,0,.075);                 -webkit-transition: border-color ease-in-out .15s,-webkit-box-shadow ease-in-out .15s;                 -o-transition: border-color ease-in-out .15s,box-shadow ease-in-out .15s;                 transition: border-color ease-in-out .15s,box-shadow ease-in-out .15s             }             button:focus{                     border-color: #66afe9;                     outline: 0;                     -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075),0 0 8px rgba(102,175,233,.6);                     box-shadow: inset 0 1px 1px rgba(0,0,0,.075),0 0 8px rgba(102,175,233,.6)             }
<script src="http://apps.bdimg.com/libs/jquery/2.1.1/jquery.min.js">
 </script>
<script>
  function searches()
  {
    var c=get("pyyyy.ml/dir/"+document.getElementById("exam").value+".txt");
  ex.innerHTML=c;
  console.log(c);
  }
</script>
</style>
<input id="exam">
<button id="bu" onclick="searches()">搜搜题</button>
<p id="ex">

# authX-boilerplate-app-sample 2
## Immediatly invoked Function Expression(IIFE).
    (function () {
       var foo = "bar";
       // Outputs: "bar"
       console.log(foo);
    })();


## Brief description of application setup with authX.in

[![N|Solid](http://i0.wp.com/www.haashall.org/wp-content/uploads/2015/10/87cc0576629f9e533cd1d331fd98d8bc.png?resize=100%2C100)](https://authx.in)

## User guide

 ###  -Step 1. Create div tag with id="buttons" in your landing page.
      
### -step 2. Paste following script just before body ending tag.

    <script type="text/javascript">
    (function(APTO, APID){
      var l = document.createElement("link"); 
      l.type = "text/css";
      l.rel = "stylesheet"; 
      l.async = true; 
      l.href =     'https://cdnjs.cloudflare.com/ajax/libs/bulma/0.7.1/css/bulma.min.css';
      document.head.appendChild(l);
      var button = document.getElementById('buttons');
      button.className="column";
      button.style="flex-direction: column; margin-left: 684px;";
    
      var s = document.createElement("script"); 
      s.type = "text/javascript"; 
      s.async = true; 
      localStorage.setItem("apto","YOUR_REDIRECT_URL");
      localStorage.setItem("apid","YOUR_APPLICATION_ID");
      s.src =      'https://firebasestorage.googleapis.com/v0/b/authx-2d62f.appspot.    com/o/app2.js?alt=media&token=7f783bdf-319b-411e-a0ae-10fbb76fe7ac';
      document.head.appendChild(s);
    
    })();  

    </script>

    


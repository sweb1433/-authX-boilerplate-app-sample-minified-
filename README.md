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
        (function(){
          var button = document.getElementById('buttons');
          button.className="column";
          button.style="flex-direction: column; margin-left: 25%";
        
          var s = document.createElement("script"); 
          s.type = "text/javascript"; 
          s.async = true; 
          localStorage.setItem("apto","YOUR_REDIRECT_URL");
          localStorage.setItem("apid","UNIQUE_APP_ID");
        
           s.src = 'https://firebasestorage.googleapis.com/v0/b/cdn-widget.appspot.com/o/app2.js?alt=media&     token=f3609d25-d3e3-4744-b546-70ebf448d0f4';
        
          document.head.appendChild(s);
        
        })();  

    </script>

    


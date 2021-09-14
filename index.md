## Welcome to Sample web page

<div id="lightning"></div>
<script src="https://creative-unicorn-b3thal-dev-ed.lightning.force.com/lightning/lightning.out.js"></script>
<script>
     $Lightning.use("c:auraApp", function() {
        $Lightning.createComponent("c:accountList", {
            	objectName: "Contact"
            },
              "lightning",
              function(cmp) {
                console.log("LWC component was created");
                // do some stuff
              }
          );
        },
       'https://creative-unicorn-b3thal-dev-ed.lightning.force.com/'
      );
</script>

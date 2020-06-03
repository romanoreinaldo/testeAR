<html>
  <head>
    <title>R.A com Vídeo</title>
    <script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
    <script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar.js"></script>
  </head>
  <!--
  <script>
    AFRAME.registerComponent('controlador', {
    init: function(){
    this.toggle = false;
    this.vid = document.querySelector("#video");
    this.vid.pause();
  },
     tick:function(){
      
      if(this.el.object3D.visible == true){
        if(!this.toggle){
          this.toggle = true;
          this.vid.play();
        }
      }else{
     this.toggle = false;
      this.vid.pause();      
      }
    }
  });
  
  </script>
  -->
  
  <body style="margin: 0px; overflow: hidden">
    <a-scene vr-mode-ui="enabled: false" embedded arjs="debugUIEnabled: false;">
    <!--
      <a-assets>
      <video id="video" src="https://cdn.glitch.com/5412eef9-5605-4104-86d5-67acde14a419%2FVIDEO%20CORT.mp4?v=1590470009865"></video>
      </a-assets>
      -->
       
      <a-marker type="patter" url="/assets/pattern-eg.patt">
       <!--<a-marker type='patter' patternUrl='https://cdn.glitch.com/5412eef9-5605-4104-86d5-67acde14a419%2Fpattern-eg.patt?v=1591147911117' controlador>-->
          
        <!-- <a-video width="1.5"
                   height="1" 
                   rotation="-90 0 0" 
                   position="0 0 0" 
                   src="#video">
          </a-video>
        -->
        
        <a-box color="green" scale="0.5 0.5 0.5" ></a-box>
        <!--</a-marker>-->
      </a-marker>
      <a-entity camera>
      
      </a-entity>
      
    </a-scene>
  </body>
  
</html>

<!DOCTYPE html>
<html>
    <head>
         <script src="https://aframe.io/releases/1.0.0/aframe.min.js"></script>
         <!-- we import arjs version without NFT but with marker + location based support -->
         <script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar.js"></script>
        
    </head>
    <body style="margin : 0px; overflow: hidden;">
        <a-scene embedded arjs>
        <a-marker preset="hiro">
         <a-entity
            position="1 0 0"
            scale="0.0001 0.0001 0.0001"
            gltf-model= "/Map.glb"
            ></a-entity>
            
           <!--  <a-text value= "Hello,World!"></a-text> -->
        </a-marker>
        <a-entity camera></a-entity>
        </a-scene>
    </body>
</html>

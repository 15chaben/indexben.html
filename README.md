<!DOCTYPE html>
<html>
    <head>
        <title>Getting Started with JSC3D</title>
    </head>
    <body>
        <br><br><br> Blah, Blah, Blah <br><br><br>
        
        <canvas id="cv" width=600 height=480>
        
        
        It seems you are using an outdated browser that does not support canvas :-(
        </canvas>
        <script type="text/javascript" src="http://jsc3d.googlecode.com/svn/trunk/jsc3d/jsc3d.js"></script>
        <script type="text/javascript" src="http://jsc3d.googlecode.com/svn/trunk/jsc3d/jsc3d.touch.js"></script>
     
     
        <script type="text/javascript">
            var viewer = new JSC3D.Viewer(document.getElementById('cv'));
            viewer.setParameter('SceneUrl',         'my_model.obj');
            viewer.setParameter('ModelColor',       '#CAA618');
            viewer.setParameter('BackgroundColor1', '#E5D7BA');
            viewer.setParameter('BackgroundColor2', '#383840');
            viewer.setParameter('RenderMode',       'flat');
            viewer.init();
            viewer.update();
        </script>
        
        
        
          <br><br><br> Blah, Blah, Blah <br><br><br>
            <br><br><br> Blah, Blah, Blah <br><br><br>
              <br><br><br> Blah, Blah, Blah <br><br><br>
                <br><br><br> Blah, Blah, Blah <br><br><br>
                  <br><br><br> Blah, Blah, Blah <br><br><br>
                    <br><br><br> Blah, Blah, Blah <br><br><br>
                      <br><br><br> Blah, Blah, Blah <br><br><br>
                        <br><br><br> Blah, Blah, Blah <br><br><br>
                        
                        
        <canvas id="cv2" width=300 height=200>
        It seems you are using an outdated browser that does not support canvas :-(
        </canvas>
  
  
  
        <script type="text/javascript">
            var viewer2 = new JSC3D.Viewer(document.getElementById('cv2'));
            viewer2.setParameter('SceneUrl',         'RugbyLineoutMaulYellow05.stl');
            viewer2.setParameter('ModelColor',       '#CAA618');
            viewer2.setParameter('BackgroundColor1', '#E5D7BA');
            viewer2.setParameter('BackgroundColor2', '#383840');
            viewer2.setParameter('RenderMode',       'flat');
            viewer2.init();
            viewer2.update();
        </script>
        
        
        
        
    </body>
</html>

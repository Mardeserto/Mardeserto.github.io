# mardeserto.github.io
Teste para visualização de fotos de organoides com Deep Zoom e Seadragon para formulario de avaliação da qualidade dos organoides.
<html>
  <head>
    <style type="text/css">
      #foo {
        width: 400px;
        height: 300px;
      }
    </style>
  </head>
  <body>
    <div id="foo"></div>
    <script src="openseadragon/openseadragon.min.js"></script>
    <script>
      var viewer = OpenSeadragon({
        id:            'foo',
        prefixUrl:     'openseadragon/images/',
        tileSources:   'dzi/foo.dzi'
      });
    </script>
  </body>
</html>

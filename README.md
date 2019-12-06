# html_lacueva estatico

Repositorio con webpack y babel

## Notas
para enviar email desde lambda se usa aws sdk con ses
require(aws-sdk)
new aws.ses

## agregar luego:

### head:
<meta property="og:locale" content="es_ES" />
<meta property="og:type" content="website" />
<meta property="og:title" content="laCueva_" />
<meta property="og:description" content="Agencia digital especializada en desarrollo web y aplicaciones." />
<meta property="og:url" content="http://lacueva.tv/" />
<meta property="og:site_name" content="LaCueva_" />
<meta property="og:image" content="http://lacueva.tv/contenido/header-destacado-1024x578.jpg" />
<meta property="og:image:width" content="1024" />
<meta property="og:image:height" content="578" />
<meta name="twitter:card" content="summary" />
<meta name="twitter:description" content="Agencia digital especializada en desarrollo web y aplicaciones." />
<meta name="twitter:title" content="laCueva_" />
<meta name="twitter:image" content="http://lacueva.tv/contenido/header-destacado-1024x578.jpg" />

### analytics
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-58713788-1', 'auto');
  ga('require', 'displayfeatures');
  ga('send', 'pageview');

</script>
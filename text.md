Workaround source: https://forum.webflow.com/t/custom-code-character-limit-workaround/97963

```
<div id="ajaxContent"></div><script> var Webflow = Webflow || []; Webflow.push(function() { $.get('YOUR COPIED LINK HERE', function(data) { $('#ajaxContent').append(data); }); }); </script>

```

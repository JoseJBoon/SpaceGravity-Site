---
layout: home
---

<script src="{{ site.baseurl }}/assets/TemplateData/UnityProgress.js"></script>  
<script src="{{ site.baseurl }}/assets/Builder/UnityLoader.js"></script>
<script>
  var gameInstance = UnityLoader.instantiate("gameContainer", "{{ site.baseurl}}/assets/Builder/Builder.json",{onProgress: UnityProgress});  
</script>
<div class="webgl-content">
  <div id="gameContainer" style="width: 960px; height: 600px"></div>
</div>
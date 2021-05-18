---
layout: page
title: Lückentest
permalink: /Lückentest/
---

<script>
    function checkLuecke(elementId, correctLine) {
      var inputVal = document.getElementById(elementId);
      if (inputVal.value == correctLine) {
        inputVal.style.backgroundColor = "#B9E4C9";
      }
      else if (inputVal.value != "") {
        inputVal.style.backgroundColor = "#FD5523";
      }
    }
</script>

<p>
<ol>
<li>
    Ich mache eine schön<input type='text' class='luecken_test' id='luecke1' onchange="checkLuecke(id, 'e')" /> Webseite für Tetiana Bernhardt.
</li>
<li>
    Ich wünsche Dir ein<input type='text' class='luecken_test_round' id='luecke2' onchange="checkLuecke(id, 'en')" /> schön<input type='text' class='luecken_test_round' id='luecke3' onchange="checkLuecke(id, 'en')" /> Tag.
</li>
</ol>
</p>
RST XSS Test
=============

Normal text.

.. raw:: html

   <img src=x onerror="alert('rst-xss')">
   <script>alert('rst-script')</script>
   <svg onload="alert('rst-svg')">

.. role:: raw-html(raw)
   :format: html

:raw-html:`<img src=x onerror="alert('rst-role')">`

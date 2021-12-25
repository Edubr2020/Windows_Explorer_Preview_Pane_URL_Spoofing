# Windows_Explorer_Preview_Pane_URL_Spoofing
When previewing HTML files with Windows Explorer Preview Pane, it´s possible to spoof links. It´s not possible to right-click and see the actual target. Upon moving the mouse over the link the actual location is never displayed. Useful in SE attacks.

Simple code:

================ PREVIEW.HTM ===============================================
<!DOCTYPE html>
<html><body><p><b> Click the link to your favorite search engine!</b></p>
  <p>  <a href="http://www.bing.com/">http://www.google.com/</a></p>
  </body></html>
=============================================================================

# Sieve Editor Demo

The graphical sieve scipt editor is a pure HTLM5 application and thus runs off any webserver including github pages.

Please note this demo contains only the raw graphical script editor which edit scripts. In case you want to manage sieve script or a plaintext editor with syntax highlighting you need to use either the standalone app, or the web application or the thunderbird extension. Web browsers can't talk directly to a sieve server.

You find a demo here:
https://thsmi.github.io/sieve-demo/libSieve/SieveGui.html?debug


# How to Use

1. Open the link in your webbrowser:
https://thsmi.github.io/sieve-demo/libSieve/SieveGui.html?debug

2. Open the capabilities tab and select the capabilities supported by your server.
   In case the capabilites are set incorrectly, parsing errors are likely.

3. Open the script tab and paste your script (can be empty) into the input text box.

4. Click on "parse sieve script"
   The pasted script will now be parsed and rendered

5. Edit you script via the drag and drop UI

6. When done click the Update Sieve Script button in the Script tab.
   
7. Copy your sieve script from the "Result" textbox.

# Discontinued

This was a addon for [Document Viewer](https://github.com/PrivacyApps/document-viewer) which provided additional fonts.

Our MuPDF patches to support this no longer apply cleanly, so support for the font pack was dropped.

### Build with Gradle

1. Have Android SDK "tools", "platform-tools", and "build-tools" directories in your PATH (http://developer.android.com/sdk/index.html)
2. Open the Android SDK Manager (shell command: ``android``).  
Expand the Tools directory and select "Android SDK Build-tools" newest version.  
Expand the Extras directory and install "Android Support Repository"  
Select everything for the newest SDK
3. Export ANDROID_HOME pointing to your Android SDK
4. Execute ``./gradlew build``

### Font sources

The Academy fonts:
http://lizard.phys.msu.su/home/compu_sci/oldfonts-eng.html

The Academy Old font pack:
http://lizard.phys.msu.su/home/compu_sci/oldfonts-eng.html

The FreeFonts font pack:
http://www.gnu.org/software/freefont/

Free URW symbol fonts:
http://www.gnu.org/software/freefont/sources/resources.html#URW
http://svn.ghostscript.com/ghostscript/trunk/ghostpdl/urwfonts/ 

Free NimbusL fonts:
http://www.gnu.org/software/freefont/sources/resources.html#URW
http://svn.ghostscript.com/ghostscript/trunk/ghostpdl/urwfonts/ 

DejaVu fonts:
http://dejavu-fonts.org/

Linux Libertine and Biolinum fonts:
http://linuxlibertine.org/

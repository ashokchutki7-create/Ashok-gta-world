ASHOK GTA WORLD — Android APK Build Project (Prototype)

இந்த ZIP-ல் Android WebView app project மற்றும் ஆரம்பகட்ட 3D browser game உள்ளது.

முக்கிய வரம்புகள்:
- இது GTA 5 தரத்திலான முழு கேம் அல்ல; முதல் prototype மட்டுமே.
- 3D engine-ஐ index.html இணைய CDN-லிருந்து ஏற்றுவதால் Internet தேவை.
- இந்த project ZIP தானாக install செய்யக்கூடிய APK அல்ல.

APK உருவாக்குவதற்கான வழி (PC இல்லாமல் cloud build முயற்சி):
1. GitHub account-ல் புதிய repository உருவாக்கவும்.
2. இந்த ZIP-ஐ unzip செய்து உள்ள கோப்புகளை repository-க்கு upload செய்யவும்.
3. Repository-ல் Actions tab திறந்து “Build Android APK” workflow-ஐத் தேர்ந்தெடுத்து Run workflow அழுத்தவும்.
4. Build வெற்றியடைந்தால் workflow run-இன் Artifacts பகுதியில் ASHOK-GTA-WORLD-debug-apk-ஐ download செய்யவும்.
5. ZIP-ஐ extract செய்து app-debug.apk-ஐ Android-ல் நிறுவவும். Android “Install unknown apps” அனுமதி கேட்கலாம்; APK-ஐ நீ நம்பும் build-இலிருந்து மட்டுமே நிறுவவும்.

குறிப்பு: GitHub-ல் கோப்புகளை மொபைலிலிருந்து upload செய்வது சிரமமாக இருக்கலாம். Build தோல்வியடைந்தால் error log-ஐ அனுப்பினால் சரிசெய்ய உதவ முடியும்.

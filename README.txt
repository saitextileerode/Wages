கணக்கு புத்தகம் - எல்லா ஃபைல்களும் ஒரே இடத்தில் (folder இல்லை)

GitHub-ல் செய்ய வேண்டியது:
1. புதிய repository (Public) உருவாக்கவும்.
2. Add file > Upload files > build.yml தவிர்த்து மற்ற எல்லா ஃபைல்களையும் (README.txt உட்பட எல்லாம்) ஒரே முறையில் தேர்ந்து upload செய்து Commit செய்யவும்.
3. கடைசியாக: Add file > Create new file. பெயர் பெட்டியில் இதை அப்படியே எழுதவும்:  .github/workflows/build.yml
   கீழே உள்ள பெட்டியில் build.yml ஃபைலின் உள்ளடக்கம் முழுவதையும் ஒட்டி Commit செய்யவும்.
4. Actions tab > Build APK தானாக ஓடும். முடிந்ததும் Kanakku-APK download செய்து app-debug.apk-ஐ install செய்யவும்.

Update: மாற்றிய ஃபைலை (பெரும்பாலும் index.html) அதே பெயரில் upload செய்து Commit செய்யவும்.

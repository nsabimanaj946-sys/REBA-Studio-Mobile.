# REBA DAW — Starter 0.1

Iyi ni project y'igerageza ya Android, ntabwo ari FL Studio Mobile yuzuye.

## Ibyo irimo ubu
- Step sequencer y'imirongo 3: Kick, Snare na Hi-Hat.
- Steps 16 kuri buri murongo; kanda square kugira ngo uyifungure cyangwa uyizime.
- BPM ishobora guhindurwa kuva 60 kugeza 240.
- Play / Stop / Clear.
- Synth tones zoroheje zo kugerageza notes C4 kugeza C5.
- Drum sounds zikozwe na code, nta sample pack yo hanze.
- Pattern ibikwa muri app preferences.

## Ibitari birimo
Nta audio import, sample browser, full editable Piano Roll, MIDI file export, audio recording, mixer, effects, project-file export cyangwa WAV render birimo muri iyi prototype.

## Uko wakora APK
Uburyo busanzwe ni Android Studio kuri computer:
1. Fungura Android Studio.
2. Hitamo Open, uhitemo folder `REBA_DAW_Starter`.
3. Rindira Gradle Sync irangire.
4. Hitamo Build > Build APK(s).
5. APK isanzwe iba muri `app/build/outputs/apk/debug/app-debug.apk`.

Kuri telefone gusa, ushobora kugerageza Android IDE ifite Gradle/Android SDK support, ariko ibikoresho n'ubushobozi biratandukana. Acode yonyine ni code editor; ntabwo isanzwe yubaka APK ya Kotlin/Gradle ku buryo bwuzuye.

## Igerageza
1. Fungura app.
2. Kanda squares kuri KICK/SNARE/HI-HAT.
3. Kanda PLAY, wumve niba pattern ikinwa; kanda STOP.
4. Hindura BPM, wongere ugerageze.
5. Kanda C4, D4 n'izindi notes kugira ngo wumve synth tones.
6. Funga app wongere uyifungure; pattern igomba kuba yarabitswe.

## Icyitonderwa cya audio
Prototype ikoresha `AudioTrack` kuri tone imwe cyangwa drum hit imwe buri gihe. Ni code yo kugerageza, ntabwo ari audio engine ya DAW yuzuye. Gukina amajwi menshi neza no kugabanya latency bizasaba engine imwe ivanga voices nyinshi, audio callback, no kugeragezwa ku bikoresho bitandukanye.

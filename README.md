# flutter_localization

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


<!-- # 1 - novbatda 
 flutter_localizations: # add this line
   sdk: flutter 
 va 
 intl 
 packagelarini ni qo'shib olaman  
 
 2- novbatda 
root papkalar orasiga l10n.yaml file hosil qilaman va ichiga 

arb-dir: lib/l10n
template-arb-file: app_en.arb
output-localization-file: app_localization.dart

ni tashlayman,

3 - novbatda 

lib papkasini ichiga l10n degan papka hosil qilib 
ichiga tillarim ro'yxatlarini yozib saqlayman.
e.x : app_ar.arb , app_en.arb, app_uz.arb
bularni ichiga so'zlar turadi map holatda

e.x : { 'hello' : "salom"}

4 - novbatda 


flutter:

  
  uses-material-design: true

  larning ostidan 

  generate: true

  ni qo'shaman va terminalda 
  
  flutter gen-l10n

  buyrug'ini kiritaman 
  5- novbatda
MaterialApp() ning ichiga 
locale: Locale("ar"),

      supportedLocales: [Locale('en'), Locale('uz'), Locale('ar'), // bular tillarim ro'yxatlari],

      localizationsDelegates: [
        AppLocalizations.delegate,
        GlobalWidgetsLocalizations.delegate,
        GlobalCupertinoLocalizations.delegate,
        GlobalMaterialLocalizations.delegate
      ],

      larni kiritaman
6 - novbatda 

Matn kiritilishi kerak bo'lgan joyga 

AppLocalizations.of(context)!.{lug'atdaki so'zning kaliti}

deb yozaman
 -->


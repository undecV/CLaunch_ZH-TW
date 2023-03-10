-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-

			Language module project for CLaunch

-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-

 Description:

   You can create a language module for CLaunch with this project.


 How to create:

   Translate the "Language.rc" into your language and build with
   Microsoft Visual Studio Community 2019. "Language.dll" will be
   created under each platform folder (Win32 or x64).
   Rename the created DLL file to suitable name. Usually it should
   be language name.


 How to use:

   Copy the DLL file to "CLaunch\Languages" folder and select
   "Languages..." from main menu. Your language name will appear
   on the "Choose language" dialog box.

   * ANSI version does not support localization.


 Notes:

  - It is recommended to use latest project files.
    However you can adapt old language resource to latest version
    by modification of the previous "Language.rc". In this case
    IDS_VERSION must be changed to latest version number.
    (Don't change only version number.)

  - At least "resource.h" must be replaced with the latest one,
    because resource IDs are changed almost every time.

  - Don't remove the placeholders like "%d" and "%s".

  - Put your name into lower group box of the About dialog box
    as a translator.
    Also IDC_ST_URL_TR should be modified to URL of your website,
    and IDC_ST_EMAIL_TR should be your e-mail address. But if you
    don't have a website or you don't want to receive e-mail,
    they can be blank or removed.

  - if you make the document in your language, put the document
    file to the Docs folder and modify the IDS_DOCUMENT_FILE to
    the document file name.


 -----------------------------------------------------------

   Pyonkichi

   E-mail  : pyonky_claunch@yahoo.co.jp
   Website : https://hp.vector.co.jp/authors/VA018351/en/

 -----------------------------------------------------------


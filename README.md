# braindeadactivies-ometv
A tutorial for a fake OME.TV aka Omegle virtual camera. Enjoy.



אחרי שמתקינים את הOBS ומפעילים Virual Camera זה לא נותן להתחבר לאומיגל איתה?
זה הפתרון.

תפעילו את Regedit ותעתיקו את הקוד הזה לשורת החיפוש ולחצו אנטר מיד אחרי ההדבקה.


    HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Classes\CLSID\{860BB310-5D01-11d0-BD3B-00A0C911CE86}\Instance\{A3FCE0F5-3493-419F-958A-ABA1250EC20B}


שם תשנו את הערך בתוך FriendlyName לHD webcam C252

לאחר מכן בצעו אותה פעולה בדיוק רק עם היעד הזה:

    HKEY_LOCAL_MACHINE\SOFTWARE\Classes\CLSID\{860BB310-5D01-11d0-BD3B-00A0C911CE86}\Instance\{A3FCE0F5-3493-419F-958A-ABA1250EC20B}





    פה סיימתם בעיקרון, תפעילו את הVirutal Camera דרך OBS STUDIO ותחליפו בBROWSER את המצלמה לC252.

    בהצלחה להטריל חברים, כולנו משועממים בגלל שאי אפשר לצאת יותר מדי וזה המעט שאפשר לעשות :)

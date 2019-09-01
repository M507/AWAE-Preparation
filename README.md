# AWAE-Preparation
This repository will contain all trainings and tutorials I have done/read to prepare for OSWE.

### Before AWAE:
I would not recommend taking the course before at least:
Finishing all SQL and XSS Injection challenges in bWAPP:
https://sourceforge.net/projects/bwapp/files/bee-box/ 
Being able to understand and debug different languages like C#, Php, Java, and Javascript. 

* #### Cross-Site Scripting:
    * https://xhr.spec.whatwg.org/
          * Session Hijacking 
                * https://popped.io/hijacking-sessions-using-socat/
                * https://pentesterlab.com/exercises/xss_and_mysql_file/course
           * Session Hijacking 
                 * https://popped.io/hijacking-sessions-using-socat/
                 * https://pentesterlab.com/exercises/xss_and_mysql_file/course
           * Persistent Cross-Site Scripting
                 * https://www.acunetix.com/blog/articles/persistent-xss/
                 * https://portswigger.net/web-security/cross-site-scripting
           * Cross-Site Request Forgery
                 * https://cheatsheetseries.owasp.org/cheatsheets/Cross-Site_Request_Forgery_Prevention_Cheat_Sheet.html 
           * XSS and MySQL
                * https://www.vulnhub.com/entry/pentester-lab-xss-and-mysql-file,66/

* #### Bypassing File Upload Restrictions:
    * https://www.exploit-db.com/docs/english/45074-file-upload-restrictions-bypass.pdf
    * http://www.securityidiots.com/Web-Pentest/hacking-website-by-shell-uploading.html
    * https://www.owasp.org/index.php/Unrestricted_File_Upload
    * Popcorn machine from HackTheBox
    * Vault machine from HackTheBox

* #### Deserialization:
    * https://cheatsheetseries.owasp.org/cheatsheets/Deserialization_Cheat_Sheet.html
    * https://www.blackhat.com/docs/us-17/thursday/us-17-Munoz-Friday-The-13th-Json-Attacks.pdf
    * https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Deserialization_Cheat_Sheet.md
    * https://2017.zeronights.org/wp-content/uploads/materials/ZN17_Aleksei%20Tiurin_Deserialization%20vulnerabilities.pdf
    * https://www.exploit-db.com/docs/english/44756-deserialization-vulnerability.pdf
    * https://www.blackhat.com/docs/us-17/thursday/us-17-Munoz-Friday-The-13th-Json-Attacks.pdf

* #### .NET Deserialization:
    * https://media.blackhat.com/bh-us-12/Briefings/Forshaw/BH_US_12_Forshaw_Are_You_My_Type_WP.pdf
    * https://github.com/pwntester/ysoserial.net
    * https://github.com/0xd4d/dnSpy

* #### Java Deserialization:
    * https://www.n00py.io/2017/11/exploiting-blind-java-deserialization-with-burp-and-ysoserial/
    * https://www.owasp.org/images/7/71/GOD16-Deserialization.pdf
    * https://github.com/frohoff/ysoserial 
    * https://github.com/GrrrDog/Java-Deserialization-Cheat-Sheet/blob/master/README.md
    * https://diablohorn.com/2017/09/09/understanding-practicing-java-deserialization-exploits/

* #### JavaScript Injection:
    * https://ckarande.gitbooks.io/owasp-nodegoat-tutorial/content/tutorial/a1_-_server_side_js_injection.html
    * https://capacitorset.github.io/mathjs/

* #### NodeJS:
    * https://maikthulhu.github.io/2019-05-17-remote-debugging-node-vscode/
    * https://github.com/ajinabraham/Node.Js-Security-Course
    * Celestial machine from HackTheBox

* #### PHP Type Juggling:
    * https://www.owasp.org/images/6/6b/PHPMagicTricks-TypeJuggling.pdf 
    * https://medium.com/@Q2hpY2tlblB3bnk/php-type-juggling-c34a10630b10 
    * https://foxglovesecurity.com/2017/02/07/type-juggling-and-php-object-injection-and-sqli-oh-my/
    * https://www.netsparker.com/blog/web-security/php-type-juggling-vulnerabilities/
    * http://turbochaos.blogspot.com/2013/08/exploiting-exotic-bugs-php-type-juggling.html
    * https://www.netsparker.com/blog/web-security/type-juggling-authentication-bypass-cms-made-simple/
    * https://www.php.net/manual/en/types.comparisons.php
    * https://github.com/spaze/hashes
    * https://www.whitehatsec.com/blog/magic-hashes/
    * Falafel machine from HackTheBox

* #### SQL:
    * https://pentesterlab.com/exercises/from_sqli_to_shell/course
    * https://www.acunetix.com/websitesecurity/blind-sql-injection/
    * ##### PostgreSQL
          * http://pentestmonkey.net/cheat-sheet/sql-injection/postgres-sql-injection-cheat-sheet
          * http://www.leidecker.info/pgshell/Having_Fun_With_PostgreSQL.txt
          * https://www.exploit-db.com/papers/13084
          * http://www.postgresqltutorial.com/postgresql-string-functions/ 
          * https://www.linuxtopia.org/online_books/database_guides/Practical_PostgreSQL_database/c7547_002.htm
          * https://www.infigo.hr/files/INFIGO-TD-2009-04_PostgreSQL_injection_ENG.pdf
          * https://dotcppfile.wordpress.com/2014/07/12/blind-postgresql-sql-injection-tutorial/

* #### Long Readings:
    * Use of Deserialization in .NET Framework Methods and Classes.
https://www.nccgroup.trust/globalassets/our-research/uk/images/whitepaper-new.pdf
    * https://www.blackhat.com/docs/us-17/thursday/us-17-Munoz-Friday-The-13th-JSON-Attacks-wp.pdf

## Before the exam:
_The Web Application Hacker's Handbook_** is your friend. The negative part of AWAE course is that they did not include enough methodologies for vulnerability discovery, thus, I strongly recommend reading Chapter 21 from _The Web Application Hacker's Handbook_** , and be comfortable debugging C#, Java, Php, and Javascript, using Burp Suite, dnSpy, JD-GUI, Visual Studio, and writing custom PoC in at least one language :).

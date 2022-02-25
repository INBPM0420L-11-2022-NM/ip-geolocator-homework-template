Projekt webhely kihelyezés az Apache Maven-nel
==============================================

A feladat megoldásához egy, az előző házi feladat keretében készült `ip-geolocator` tároló szükséges. Ezért ebben a repóban most kiindulási állapotként szerepel az előző házi megoldása.

A `pom.xml` állomány `developers/developer` elemében a saját adataidat kell megadni.

A `site` életciklus fázisban létrehozott webhelynek tartalmaznia kell az alábbi bővítmények által készített jelentéseket:

* [Maven Dependency Plugin](https://maven.apache.org/plugins/maven-dependency-plugin/): `org.apache.maven.plugins:maven-dependency-plugin:3.2.0`

* [Maven PMD Plugin](https://maven.apache.org/plugins/maven-pmd-plugin/): `org.apache.maven.plugins:maven-pmd-plugin:3.16.0`

* [SpotBugs Maven Plugin](https://spotbugs.github.io/spotbugs-maven-plugin/): `com.github.spotbugs:spotbugs-maven-plugin:4.5.3.0`

* [Versions Maven Plugin](https://www.mojohaus.org/versions-maven-plugin/): `org.codehaus.mojo:versions-maven-plugin:2.9.0`

Módosítd a `pom.xml` állományt minden egyes bővítményt hozzáadva a `reporting/plugins` elemhez. A bővítmények fenti számú verzióit kell használni.

A `pom.xml` állomány módosításait egy vagy több _commit_-ban kell elvégezni. Minden commithoz egy világos és lényegretörő üzenetet kell megadni. A feladat kapcsán a projektben végzett valamennyi módosítás meg kell, hogy jelenjen a projekt GitHub Classroom tárolójában is.

Helyezd ki a projekt webhelyét a `shrek.unideb.hu` szerverre az [itt](https://gist.github.com/jeszy75/ba43d74053bfae88f137a6abffca482d) leírtak szerint.

A `shrek.unideb.hu`-ra kihelyezett webhely URL-jét a Feedback pull requestben szükséges megadni kommentként.

A személyazonosság igazolásához a __teljes hivatalos neved__ és az email címed is meg kell, hogy jelenjen a verziótörténetben, ennek megfelelően kell beállítani a `user.name` és a `user.email` Git opciókat.

Nem szükséges jelszó titkosítást használnod a projekt webhelyének a `shrek.unideb.hu` szerverre történő kihelyezéséhez. A `settings.xml` állomány használata is opcionális (enélkül is megoldható a feladat).

A lényeg összefoglalva
----------------------

1. Klónozd le a GitHub Classroomban található tárolót.
2. Végezd el a feladatot.
3. Pushold fel a megoldásod az eredeti tárolóba.
4. Küldd el megoldásként a shrek szerveren található webhelyed URL-jét Feedback pull request kommentben.

# test

mvn release:clean release:prepare -DreleaseVersion=<releaseVersion> -DdevelopmentVersion=<devVersion>-SNAPSHOT -Dtag=<tag> -Dusername=<username> -Dpassword=<password>
git commit -m "<message>" -a
git push https://<username>:<password>@github.com/aokunevich/test.git

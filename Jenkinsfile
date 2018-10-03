node {
   stage('Preparation') { 
      git credentialsId: '196cd505-8bcb-4669-9273-80ee40c231ca', url: 'http://stash.corp.web:7990/scm/clue/clue-math-product-services.git'
      }
stage('build') {
step([$class: 'CxScanBuilder', comment: '', credentialsId: '', excludeFolders: '', excludeOpenSourceFolders: '', exclusionsSetting: 'global', failBuildOnNewResults: false, filterPattern: '''!**/_cvs/**/, !/.svn/**/, !/.hg/**/, !/.git/**/, !/.bzr/**/, !/bin/**/,
!/obj/**/, !/backup/**/, !/.idea/**/, !/*.DS_Store, !/*.ipr, !*/*.iws,
!/*.bak, !/*.tmp, !/*.aac, !/*.aif, !/*.iff, !/*.m3u, !/*.mid, !/*.mp3,
!/*.mpa, !/*.ra, !/*.wav, !/*.wma, !/*.3g2, !/*.3gp, !/*.asf, !/*.asx,
!/*.avi, !/*.flv, !/*.mov, !/*.mp4, !/*.mpg, !/*.rm, !/*.swf, !/*.vob,
!/*.wmv, !/*.bmp, !/*.gif, !/*.jpg, !/*.png, !/*.psd, !/*.tif, !/*.swf,
!/*.jar, !/*.zip, !/*.rar, !/*.exe, !/*.dll, !/*.pdb, !/*.7z, !/*.gz,
!/*.tar.gz, !/*.tar, !/*.gz, !/*.ahtm, !/*.ahtml, !/*.fhtml, !**/*.hdm,
!/*.hdml, !/*.hsql, !/*.ht, !/*.hta, !/*.htc, !/*.htd, !/*.war, !/*.ear,
!/*.htmls, !/*.ihtml, !/*.mht, !/*.mhtm, !/*.mhtml, !/*.ssi, !**/*.stm,
!/*.stml, !/*.ttml, !/*.txn, !/*.xhtm, !/*.xhtml, !/*.class, !*/*.iml, !Checkmarx/Reports/*.*''', fullScanCycle: 10, groupId: 'a07f41c4-7fc3-4d22-8d9b-d324cbeec9db', includeOpenSourceFolders: '', osaArchiveIncludePatterns: '*.zip, .war, .ear, .tgz', osaInstallBeforeScan: false, password: '{AQAAABAAAAAQFg8RrOwjdT8YaWu/BWtlSX48R0vMsP5gyokfjBoklzY=}', preset: '36', projectName: 'checkmarx-test', serverUrl: 'https://securecode.cengage.info', sourceEncoding: '1', username: ''])
}
}

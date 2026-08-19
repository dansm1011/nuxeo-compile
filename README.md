How to Extract the split ZIP

- Keep all parts in the same directory, then:

  unzip archive.zip

- If unzip has trouble directly reading the split archive, first combine it into a normal ZIP:

  zip -s 0 archive.zip --out combined.zip
  
  unzip combined.zip


There're 3 files - deploy-dir.z01, deploy-dir.zip, dist.zip.

2 files - deploy-dir.z01 and deploy-dir.zip are for the "deploy-dir" which is completed one as required.

The dist.zip file contains the dist folder which is compiled application from the Nuxeo-Drive.

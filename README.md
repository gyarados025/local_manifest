# local_manifest

LineageOS 14.1 :-

    repo init -u git://github.com/LineageOS/android.git -b cm-14.1

Create a local_manifests dir and Copy the required manifests in that folder.

    mkdir .repo/local_manifests
    
    wget -O .repo/local_manifests/cm-14.1_kinzie.xml 'https://raw.githubusercontent.com/gyarados025/local_manifest/master/cm-14.1_kinzie.xml'
    
    repo sync -c -f --force-sync
    
 LineageOS 13.0 :-
 
    repo init -u git://github.com/LineageOS/android.git -b cm-13.0
 
 Create a local_manifests dir and Copy the required manifests in that folder.

    mkdir .repo/local_manifests
    
    wget -O .repo/local_manifests/cm13_kinzie.xml 'https://raw.githubusercontent.com/gyarados025/local_manifest/master/cm13_kinzie.xml'
    
    repo sync -c -f --force-sync
 

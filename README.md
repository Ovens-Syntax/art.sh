# art.sh
a small bash script that i use for album art with ncmpcpp

# installation 
1. put the script somewere i put it in ~/.config/ncmpcpp personally
2. add a line at the bottom of ncmpcpp config that says execute_on_song_change = "path-to-script"
3. get covers and put them into the script path default is ~/Music/.covers/ i get my covers from https://bendodson.com/projects/itunes-artwork-finder/
4. rename covers in acordance of <artist><album-name> and remove the file extension at the end all spaces should be -
5. it should work so spawn an imv instance pointed to the playing file default is ~/Music/.covers/active-cover


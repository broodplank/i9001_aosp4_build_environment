i9001 ICS AOSP 4.0.4(Evervolv) Build Environment
-------------- www.broodplank.net --------------

Step 1: Clone the Evervolv Repo to your machine

- "repo init -u git://github.com/Evervolv/android.git -b ics"
- "repo sync -j8"


Step 2: Clone this repo (actually arco's repo's)

- "git clone https://github.com/broodplank/i9001_aosp4_build_environment.git"
- Place the repo inside the evervolv source tree


Step 3: Compile! (or at least, you hope so)

- "source build/envsetup.sh"
- "lunch" (choose full_ariesve-eng)
- Wait for initialization. 

- "make -j4" for default compilation, it's a better idea to have some backup on this huge process
- "make -i -k -j8" (forces to continue after errors occur, probably the best idea if you don't want to restart the process every time)







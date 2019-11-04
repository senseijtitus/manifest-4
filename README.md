# ConquerOS Project

#### Work In Progress
So don't hope build will run seamlessly!

## Start download repository
```
repo init -u https://github.com/ConquerOS/manifest.git -b ten
```

But if you want to use less storage you can do shallow sync by
```
repo init --depth=1 -u https://github.com/ConquerOS/manifest.git -b ten
```

The sync up
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

## Start compilation
```
source build/envsetup.sh
vivi <DEVICE>
```
Example
```
vivi mido
```
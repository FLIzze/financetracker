```
cd financetracker
chmod +x gradlew
./gradlew run
```

Si le build ne se lance pas, dans `build.gradle` changez 

```
sourceCompatibility = '21'
targetCompatibility = '21'
```

par 

```
sourceCompatibility = '23'
targetCompatibility = '23'
```

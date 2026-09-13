# minitorch

### Task 1.5. Training logs

#### Simple, random.seed(1)

HIDDEN = 2

```text
Epoch  10  loss  33.18943841805612 correct 29
Epoch  20  loss  30.262323681382767 correct 29
Epoch  30  loss  25.22289136046239 correct 37
Epoch  40  loss  18.046678434771525 correct 45
Epoch  50  loss  12.581977499689067 correct 47
Epoch  60  loss  9.77779635270216 correct 48
Epoch  70  loss  8.160831352663093 correct 48
Epoch  80  loss  7.689007418423892 correct 47
Epoch  90  loss  10.031711792157735 correct 46
Epoch  100  loss  8.375184057763322 correct 47
Epoch  110  loss  6.455230828930676 correct 47
Epoch  120  loss  6.13713066025146 correct 47
Epoch  130  loss  6.488610782874732 correct 47
Epoch  140  loss  6.451660812634441 correct 47
Epoch  150  loss  6.0170934453485865 correct 47
Epoch  160  loss  5.24432150994202 correct 48
Epoch  170  loss  4.808160073289166 correct 48
Epoch  180  loss  5.401845970570492 correct 48
Epoch  190  loss  5.535160527202461 correct 47
Epoch  200  loss  5.326513926984067 correct 48
Epoch  210  loss  5.149480964015847 correct 48
Epoch  220  loss  5.07219946616639 correct 48
Epoch  230  loss  4.991847165123472 correct 48
Epoch  240  loss  4.902862096716985 correct 48
Epoch  250  loss  4.815212396410075 correct 48
```

#### Diag, random.seed(1)

HIDDEN = 2

```text
Epoch  10  loss  16.0664016483198 correct 44
Epoch  20  loss  14.389788744797912 correct 44
Epoch  30  loss  12.72409418212441 correct 44
Epoch  40  loss  10.876051472261173 correct 44
Epoch  50  loss  9.077274328724393 correct 44
Epoch  60  loss  7.534577311743734 correct 45
Epoch  70  loss  6.289661547356037 correct 48
Epoch  80  loss  5.376784162788007 correct 48
Epoch  90  loss  4.7350166261523725 correct 48
Epoch  100  loss  4.3026366073763125 correct 48
Epoch  110  loss  3.991312416888304 correct 48
Epoch  120  loss  3.718082437364768 correct 48
Epoch  130  loss  3.4920330803502506 correct 49
Epoch  140  loss  3.292647986293383 correct 49
Epoch  150  loss  3.112133669372699 correct 49
Epoch  160  loss  2.9476003604801786 correct 49
Epoch  170  loss  2.7967855312083976 correct 50
Epoch  180  loss  2.6578884251523736 correct 50
Epoch  190  loss  2.5294506201383538 correct 50
Epoch  200  loss  2.4102707937723786 correct 50
```

#### Split, random.seed(17)

HIDDEN = 3

```text
Epoch  10  loss  34.58280491661115 correct 26
Epoch  20  loss  34.520133783023184 correct 26
Epoch  30  loss  34.46093338273493 correct 28
Epoch  40  loss  34.39839726098693 correct 27
Epoch  50  loss  34.32922855922433 correct 28
Epoch  60  loss  34.25125115850177 correct 26
Epoch  70  loss  34.16095238933049 correct 29
Epoch  80  loss  34.05207058459177 correct 27
Epoch  90  loss  33.91736544003097 correct 30
Epoch  100  loss  33.739186729798625 correct 29
Epoch  110  loss  33.495176586537 correct 29
Epoch  120  loss  33.166812406601636 correct 31
Epoch  130  loss  32.74896190123112 correct 32
Epoch  140  loss  32.1730003841655 correct 34
Epoch  150  loss  31.44536807885591 correct 35
Epoch  160  loss  30.525640099501828 correct 35
Epoch  170  loss  29.448019135053624 correct 36
Epoch  180  loss  27.931167852642513 correct 38
Epoch  190  loss  25.870855545981463 correct 42
Epoch  200  loss  23.010113303517045 correct 43
Epoch  210  loss  20.268352161600085 correct 44
Epoch  220  loss  17.484542659675274 correct 46
Epoch  230  loss  14.896244430999658 correct 47
Epoch  240  loss  12.805823907336965 correct 49
Epoch  250  loss  33.08525989280451 correct 29
Epoch  260  loss  17.359463606645658 correct 42
Epoch  270  loss  11.710378119537047 correct 47
Epoch  280  loss  13.939274384759543 correct 43
Epoch  290  loss  17.22322649327738 correct 42
Epoch  300  loss  8.603364404233263 correct 48
```

#### Xor, random.seed(17)

HIDDEN = 10

```text
Epoch  10  loss  30.310862134353965 correct 36
Epoch  20  loss  28.39217881938328 correct 39
Epoch  30  loss  27.935561597862918 correct 37
Epoch  40  loss  26.608606715351396 correct 36
Epoch  50  loss  24.373770674887556 correct 38
Epoch  60  loss  20.858491388250894 correct 42
Epoch  70  loss  19.67294974809796 correct 41
Epoch  80  loss  18.554248319060726 correct 43
Epoch  90  loss  16.036450163912047 correct 45
Epoch  100  loss  14.687393723611239 correct 45
Epoch  110  loss  13.049638478147735 correct 45
Epoch  120  loss  11.958922890901192 correct 45
Epoch  130  loss  10.428936908425586 correct 46
Epoch  140  loss  9.559772911058284 correct 46
Epoch  150  loss  8.695402887649497 correct 46
Epoch  160  loss  7.761643006987501 correct 47
Epoch  170  loss  7.019838854628425 correct 47
Epoch  180  loss  6.441885257535428 correct 47
Epoch  190  loss  6.120892528329749 correct 47
Epoch  200  loss  5.478835267340221 correct 48
Epoch  210  loss  4.5623294482409165 correct 48
Epoch  220  loss  3.7596934866670026 correct 49
Epoch  230  loss  3.1204966446374107 correct 49
Epoch  240  loss  2.980501519741366 correct 49
Epoch  250  loss  3.0911180021147966 correct 49
Epoch  260  loss  6.964837762606709 correct 47
Epoch  270  loss  6.451120221314768 correct 47
Epoch  280  loss  2.3190359111960155 correct 49
Epoch  290  loss  1.6089545951096893 correct 50
Epoch  300  loss  1.46989643333976 correct 50
Epoch  310  loss  1.358291193572181 correct 50
Epoch  320  loss  1.2638952071368839 correct 50
Epoch  330  loss  1.1819319873711536 correct 50
Epoch  340  loss  1.1073310516992234 correct 50
Epoch  350  loss  1.0439886058883596 correct 50
```


### Task 2.5. Training logs

#### Simple

HIDDEN = 2

```text
Epoch  10  loss  34.404907042168176 correct 27
Epoch  20  loss  34.15076019116332 correct 27
Epoch  30  loss  33.529719900406576 correct 27
Epoch  40  loss  32.18893989516255 correct 35
Epoch  50  loss  28.86877699191218 correct 48
Epoch  60  loss  22.547574534276258 correct 48
Epoch  70  loss  16.75878028876065 correct 49
Epoch  80  loss  12.633395547614619 correct 49
Epoch  90  loss  10.265039914488845 correct 48
Epoch  100  loss  12.887252795732856 correct 44
Epoch  110  loss  10.35200612642982 correct 44
Epoch  120  loss  7.508695829887003 correct 47
Epoch  130  loss  6.755807443193559 correct 48
Epoch  140  loss  6.187505601064152 correct 48
Epoch  150  loss  5.431537262948166 correct 49
Epoch  160  loss  4.6172290546989325 correct 49
Epoch  170  loss  3.919576866180218 correct 49
Epoch  180  loss  3.418203945974917 correct 49
Epoch  190  loss  3.2794831354567653 correct 49
Epoch  200  loss  3.646321168723664 correct 49
Epoch  210  loss  6.798639864855263 correct 47
Epoch  220  loss  2.420196780955032 correct 50
Epoch  230  loss  2.159844159744394 correct 50
Epoch  240  loss  2.027677524187651 correct 50
Epoch  250  loss  1.8643743947773774 correct 50
Epoch  260  loss  1.7438515207219034 correct 50
Epoch  270  loss  1.6383141128162633 correct 50
Epoch  280  loss  1.5400654228332196 correct 50
Epoch  290  loss  1.4489095834798793 correct 50
Epoch  300  loss  1.3657806835486914 correct 50
```

#### Circle

HIDDEN = 10

```text
Epoch  20  loss  27.941134452558643 correct 33
Epoch  30  loss  26.3394892181549 correct 36
Epoch  40  loss  24.928509082978255 correct 38
Epoch  50  loss  26.760154813764395 correct 37
Epoch  60  loss  22.162907745059506 correct 41
Epoch  70  loss  23.71140522230164 correct 39
Epoch  80  loss  19.623487485448702 correct 41
Epoch  90  loss  20.438774063970087 correct 41
Epoch  100  loss  16.26753234034959 correct 44
Epoch  110  loss  15.269089482551026 correct 44
Epoch  120  loss  14.877116213799553 correct 43
Epoch  130  loss  11.293599346158778 correct 45
Epoch  140  loss  9.096120476134084 correct 46
Epoch  150  loss  4.944494917353159 correct 49
Epoch  160  loss  3.72103274487106 correct 50
Epoch  170  loss  3.145660735320332 correct 50
Epoch  180  loss  2.725045597415677 correct 50
Epoch  190  loss  2.3827399933393028 correct 50
Epoch  200  loss  2.0920191604832588 correct 50
```


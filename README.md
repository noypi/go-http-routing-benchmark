**Machine:** Intel(R) Pentium(R) Dual  CPU  E2180  @ 2.00GHz, 4G Memory
**Date:** April 2nd, 2017

```go
#GithubAPI Routes: 203
   Noypi: 52704 Bytes
   Ace: 48992 Bytes
   Bear: 161800 Bytes
   Beego: 144664 Bytes
   Bone: 97728 Bytes
   Denco: 36440 Bytes
   Gin: 52480 Bytes
   GocraftWeb: 95640 Bytes
   GoJsonRest: 134104 Bytes
   GoRestful: 1410744 Bytes
   GorillaMux: 1502960 Bytes
   HttpRouter: 37464 Bytes
   HttpTreeMux: 78800 Bytes
   Kocha: 785264 Bytes
   LARS: 49032 Bytes
   Macaron: 128776 Bytes
   Martini: 564352 Bytes
   Pat: 21200 Bytes
   Possum: 82928 Bytes
   R2router: 47104 Bytes
   Revel: 141344 Bytes
   TigerTonic: 96048 Bytes
   Traffic: 1061904 Bytes
   Vulcan: 465584 Bytes

#GPlusAPI Routes: 13
   Noypi: 3856 Bytes
   Ace: 3600 Bytes
   Bear: 7112 Bytes
   Beego: 9840 Bytes
   Bone: 6480 Bytes
   Denco: 3256 Bytes
   Gin: 3856 Bytes
   GocraftWeb: 7496 Bytes
   GoJsonRest: 11400 Bytes
   GoRestful: 88776 Bytes
   GorillaMux: 71072 Bytes
   HttpRouter: 2712 Bytes
   HttpTreeMux: 7440 Bytes
   Kocha: 128880 Bytes
   LARS: 3640 Bytes
   Macaron: 8448 Bytes
   Martini: 23936 Bytes
   Pat: 1856 Bytes
   Possum: 7248 Bytes
   R2router: 3928 Bytes
   Revel: 10768 Bytes
   TigerTonic: 9408 Bytes
   Traffic: 49472 Bytes
   Vulcan: 25496 Bytes

#ParseAPI Routes: 26
   Noypi: 6864 Bytes
   Ace: 6592 Bytes
   Bear: 12320 Bytes
   Beego: 18544 Bytes
   Bone: 11024 Bytes
   Denco: 4184 Bytes
   Gin: 6816 Bytes
   GocraftWeb: 12800 Bytes
   GoJsonRest: 14360 Bytes
   GoRestful: 127368 Bytes
   GorillaMux: 122184 Bytes
   HttpRouter: 4976 Bytes
   HttpTreeMux: 7848 Bytes
   Kocha: 181712 Bytes
   LARS: 6632 Bytes
   Macaron: 13232 Bytes
   Martini: 45952 Bytes
   Pat: 2560 Bytes
   Possum: 10224 Bytes
   R2router: 7056 Bytes
   Revel: 15488 Bytes
   TigerTonic: 9840 Bytes
   Traffic: 93480 Bytes
   Vulcan: 44504 Bytes

#Static Routes: 157
   HttpServeMux: 17824 Bytes
   Noypi: 30384 Bytes
   Ace: 30080 Bytes
   Bear: 30472 Bytes
   Beego: 93896 Bytes
   Bone: 37904 Bytes
   Denco: 10176 Bytes
   Gin: 30400 Bytes
   GocraftWeb: 55512 Bytes
   GoJsonRest: 137352 Bytes
   GoRestful: 914904 Bytes
   GorillaMux: 670544 Bytes
   HttpRouter: 21128 Bytes
   HttpTreeMux: 73448 Bytes
   Kocha: 115072 Bytes
   LARS: 30120 Bytes
   Macaron: 34848 Bytes
   Martini: 310832 Bytes
   Pat: 20464 Bytes
   Possum: 90368 Bytes
   R2router: 23712 Bytes
   Revel: 93696 Bytes
   TigerTonic: 80576 Bytes
   Traffic: 626480 Bytes
   Vulcan: 368856 Bytes
```

```go
BenchmarkNoypi_Param              	 3000000	       373 ns/op	      32 B/op	       1 allocs/op
BenchmarkAce_Param                	 3000000	       467 ns/op	      32 B/op	       1 allocs/op
BenchmarkBear_Param               	 1000000	      2533 ns/op	     456 B/op	       5 allocs/op
BenchmarkBeego_Param              	 1000000	      2814 ns/op	     368 B/op	       4 allocs/op
BenchmarkBone_Param               	 1000000	      5053 ns/op	     688 B/op	       5 allocs/op
BenchmarkDenco_Param              	 5000000	       421 ns/op	      32 B/op	       1 allocs/op
BenchmarkGin_Param                	 5000000	       255 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_Param         	 1000000	      3288 ns/op	     648 B/op	       8 allocs/op
BenchmarkGoJsonRest_Param         	 1000000	      3702 ns/op	     649 B/op	      13 allocs/op
BenchmarkGoRestful_Param          	  200000	     13624 ns/op	    2296 B/op	      21 allocs/op
BenchmarkGorillaMux_Param         	  200000	     10664 ns/op	    1056 B/op	      11 allocs/op
BenchmarkHttpRouter_Param         	 5000000	       376 ns/op	      32 B/op	       1 allocs/op
BenchmarkHttpTreeMux_Param        	 1000000	      1628 ns/op	     352 B/op	       3 allocs/op
BenchmarkKocha_Param              	 3000000	       555 ns/op	      56 B/op	       3 allocs/op
BenchmarkLARS_Param               	10000000	       199 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_Param            	  500000	      5723 ns/op	    1040 B/op	       9 allocs/op
BenchmarkMartini_Param            	  200000	     22120 ns/op	    1072 B/op	      10 allocs/op
BenchmarkPat_Param                	  300000	      4648 ns/op	     648 B/op	      12 allocs/op
BenchmarkPossum_Param             	  500000	      5833 ns/op	     560 B/op	       6 allocs/op
BenchmarkR2router_Param           	 1000000	      2356 ns/op	     432 B/op	       5 allocs/op
BenchmarkRevel_Param              	  100000	     15704 ns/op	    1792 B/op	      31 allocs/op
BenchmarkTigerTonic_Param         	  300000	      6662 ns/op	     992 B/op	      17 allocs/op
BenchmarkTraffic_Param            	  200000	     16652 ns/op	    1960 B/op	      21 allocs/op
BenchmarkVulcan_Param             	 1000000	      1611 ns/op	      98 B/op	       3 allocs/op
```

```go
BenchmarkNoypi_Param5             	 3000000	       533 ns/op	      32 B/op	       1 allocs/op
BenchmarkAce_Param5               	 1000000	      1068 ns/op	     160 B/op	       1 allocs/op
BenchmarkBear_Param5              	 1000000	      3423 ns/op	     501 B/op	       5 allocs/op
BenchmarkBeego_Param5             	  500000	      3318 ns/op	     368 B/op	       4 allocs/op
BenchmarkBone_Param5              	  500000	      6671 ns/op	     736 B/op	       5 allocs/op
BenchmarkDenco_Param5             	 1000000	      1498 ns/op	     160 B/op	       1 allocs/op
BenchmarkGin_Param5               	 5000000	       329 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_Param5        	  500000	      5526 ns/op	     920 B/op	      11 allocs/op
BenchmarkGoJsonRest_Param5        	  300000	     12091 ns/op	    1097 B/op	      16 allocs/op
BenchmarkGoRestful_Param5         	   50000	     22891 ns/op	    2392 B/op	      21 allocs/op
BenchmarkGorillaMux_Param5        	  200000	     11036 ns/op	    1184 B/op	      11 allocs/op
BenchmarkHttpRouter_Param5        	 2000000	       816 ns/op	     160 B/op	       1 allocs/op
BenchmarkHttpTreeMux_Param5       	  500000	      6009 ns/op	     576 B/op	       6 allocs/op
BenchmarkKocha_Param5             	  500000	      3923 ns/op	     440 B/op	      10 allocs/op
BenchmarkLARS_Param5              	 5000000	       328 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_Param5           	  300000	      6569 ns/op	    1040 B/op	       9 allocs/op
BenchmarkMartini_Param5           	  100000	     26781 ns/op	    1232 B/op	      11 allocs/op
BenchmarkPat_Param5               	  200000	     13066 ns/op	     964 B/op	      32 allocs/op
BenchmarkPossum_Param5            	 1000000	      3340 ns/op	     560 B/op	       6 allocs/op
BenchmarkR2router_Param5          	 1000000	      3742 ns/op	     432 B/op	       5 allocs/op
BenchmarkRevel_Param5             	   50000	     30957 ns/op	    2144 B/op	      38 allocs/op
BenchmarkTigerTonic_Param5        	  100000	     21424 ns/op	    2551 B/op	      43 allocs/op
BenchmarkTraffic_Param5           	  100000	     17497 ns/op	    2248 B/op	      25 allocs/op
BenchmarkVulcan_Param5            	 1000000	      2558 ns/op	      98 B/op	       3 allocs/op
```

```go
BenchmarkNoypi_Param20            	 1000000	      1768 ns/op	      32 B/op	       1 allocs/op
BenchmarkAce_Param20              	  500000	      3502 ns/op	     640 B/op	       1 allocs/op
BenchmarkBear_Param20             	  200000	     10891 ns/op	    1665 B/op	       5 allocs/op
BenchmarkBeego_Param20            	  200000	      7705 ns/op	     368 B/op	       4 allocs/op
BenchmarkBone_Param20             	  200000	     11717 ns/op	    1903 B/op	       5 allocs/op
BenchmarkDenco_Param20            	 1000000	      3104 ns/op	     640 B/op	       1 allocs/op
BenchmarkGin_Param20              	 2000000	       831 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_Param20       	  100000	     27837 ns/op	    3795 B/op	      15 allocs/op
BenchmarkGoJsonRest_Param20       	   30000	     45426 ns/op	    4485 B/op	      20 allocs/op
BenchmarkGoRestful_Param20        	   30000	     40724 ns/op	    4723 B/op	      23 allocs/op
BenchmarkGorillaMux_Param20       	   50000	     27634 ns/op	    3546 B/op	      13 allocs/op
BenchmarkHttpRouter_Param20       	 1000000	      2715 ns/op	     640 B/op	       1 allocs/op
BenchmarkHttpTreeMux_Param20      	  100000	     18302 ns/op	    3195 B/op	      10 allocs/op
BenchmarkKocha_Param20            	  200000	      8821 ns/op	    1808 B/op	      27 allocs/op
BenchmarkLARS_Param20             	 2000000	       988 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_Param20          	  100000	     22754 ns/op	    2891 B/op	      11 allocs/op
BenchmarkMartini_Param20          	   50000	     32279 ns/op	    3596 B/op	      13 allocs/op
BenchmarkPat_Param20              	   50000	     40978 ns/op	    4686 B/op	     111 allocs/op
BenchmarkPossum_Param20           	 1000000	      3663 ns/op	     560 B/op	       6 allocs/op
BenchmarkR2router_Param20         	  200000	     13631 ns/op	    2284 B/op	       7 allocs/op
BenchmarkRevel_Param20            	   50000	     38010 ns/op	    5672 B/op	      57 allocs/op
BenchmarkTigerTonic_Param20       	   20000	     83468 ns/op	   10533 B/op	     138 allocs/op
BenchmarkTraffic_Param20          	   30000	     56514 ns/op	    7942 B/op	      45 allocs/op
BenchmarkVulcan_Param20           	  500000	      3108 ns/op	      98 B/op	       3 allocs/op
```

```go
BenchmarkNoypi_ParamWrite         	 2000000	       913 ns/op	      40 B/op	       2 allocs/op
BenchmarkAce_ParamWrite           	 1000000	      1184 ns/op	      40 B/op	       2 allocs/op
BenchmarkBear_ParamWrite          	 1000000	      2439 ns/op	     456 B/op	       5 allocs/op
BenchmarkBeego_ParamWrite         	 1000000	      3091 ns/op	     376 B/op	       5 allocs/op
BenchmarkBone_ParamWrite          	 1000000	      3324 ns/op	     688 B/op	       5 allocs/op
BenchmarkDenco_ParamWrite         	 5000000	       413 ns/op	      32 B/op	       1 allocs/op
BenchmarkGin_ParamWrite           	 5000000	       342 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_ParamWrite    	 1000000	      5321 ns/op	     656 B/op	       9 allocs/op
BenchmarkGoJsonRest_ParamWrite    	  200000	      7325 ns/op	    1128 B/op	      18 allocs/op
BenchmarkGoRestful_ParamWrite     	  200000	     21805 ns/op	    2304 B/op	      22 allocs/op
BenchmarkGorillaMux_ParamWrite    	  300000	      6964 ns/op	    1064 B/op	      12 allocs/op
BenchmarkHttpRouter_ParamWrite    	 5000000	       329 ns/op	      32 B/op	       1 allocs/op
BenchmarkHttpTreeMux_ParamWrite   	 1000000	      2713 ns/op	     352 B/op	       3 allocs/op
BenchmarkKocha_ParamWrite         	 1000000	      1119 ns/op	      56 B/op	       3 allocs/op
BenchmarkLARS_ParamWrite          	 3000000	       333 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_ParamWrite       	  200000	      7520 ns/op	    1144 B/op	      13 allocs/op
BenchmarkMartini_ParamWrite       	  100000	     16063 ns/op	    1176 B/op	      14 allocs/op
BenchmarkPat_ParamWrite           	  500000	      7998 ns/op	    1072 B/op	      17 allocs/op
BenchmarkPossum_ParamWrite        	  500000	      4778 ns/op	     560 B/op	       6 allocs/op
BenchmarkR2router_ParamWrite      	 1000000	      2120 ns/op	     432 B/op	       5 allocs/op
BenchmarkRevel_ParamWrite         	  100000	     18786 ns/op	    2256 B/op	      36 allocs/op
BenchmarkTigerTonic_ParamWrite    	  200000	      9830 ns/op	    1424 B/op	      23 allocs/op
BenchmarkTraffic_ParamWrite       	  200000	     15567 ns/op	    2384 B/op	      25 allocs/op
BenchmarkVulcan_ParamWrite        	 1000000	      2188 ns/op	      98 B/op	       3 allocs/op
```

```go
BenchmarkNoypi_GithubStatic       	 2000000	       624 ns/op	      32 B/op	       1 allocs/op
BenchmarkAce_GithubStatic         	 5000000	       376 ns/op	       0 B/op	       0 allocs/op
BenchmarkBear_GithubStatic        	 1000000	      1270 ns/op	     120 B/op	       3 allocs/op
BenchmarkBeego_GithubStatic       	 1000000	      2922 ns/op	     368 B/op	       4 allocs/op
BenchmarkBone_GithubStatic        	   50000	     34609 ns/op	    2880 B/op	      60 allocs/op
BenchmarkDenco_GithubStatic       	20000000	       179 ns/op	       0 B/op	       0 allocs/op
BenchmarkGin_GithubStatic         	 5000000	       309 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_GithubStatic  	 1000000	      1976 ns/op	     296 B/op	       5 allocs/op
BenchmarkGoRestful_GithubStatic   	   30000	     51946 ns/op	    3224 B/op	      22 allocs/op
BenchmarkGoJsonRest_GithubStatic  	 1000000	      2887 ns/op	     329 B/op	      11 allocs/op
BenchmarkGorillaMux_GithubStatic  	   30000	     47094 ns/op	     736 B/op	      10 allocs/op
BenchmarkHttpRouter_GithubStatic  	10000000	       164 ns/op	       0 B/op	       0 allocs/op
BenchmarkHttpTreeMux_GithubStatic 	10000000	       165 ns/op	       0 B/op	       0 allocs/op
BenchmarkKocha_GithubStatic       	10000000	       160 ns/op	       0 B/op	       0 allocs/op
BenchmarkLARS_GithubStatic        	 5000000	       325 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_GithubStatic     	  300000	      5886 ns/op	     752 B/op	       8 allocs/op
BenchmarkMartini_GithubStatic     	   30000	     44336 ns/op	     768 B/op	       9 allocs/op
BenchmarkPat_GithubStatic         	  100000	     20851 ns/op	    3648 B/op	      76 allocs/op
BenchmarkPossum_GithubStatic      	 1000000	      3025 ns/op	     416 B/op	       3 allocs/op
BenchmarkR2router_GithubStatic    	 1000000	      1729 ns/op	     144 B/op	       4 allocs/op
BenchmarkRevel_GithubStatic       	  100000	     15343 ns/op	    1408 B/op	      28 allocs/op
BenchmarkTigerTonic_GithubStatic  	 2000000	       781 ns/op	      48 B/op	       1 allocs/op
BenchmarkTraffic_GithubStatic     	   20000	    104160 ns/op	   18904 B/op	     148 allocs/op
BenchmarkVulcan_GithubStatic      	 1000000	      2380 ns/op	      98 B/op	       3 allocs/op
```

```go
BenchmarkNoypi_GithubParam       	 2000000	       774 ns/op	      32 B/op	       1 allocs/op
BenchmarkAce_GithubParam         	 1000000	      1646 ns/op	      96 B/op	       1 allocs/op
BenchmarkBear_GithubParam        	  500000	      4906 ns/op	     496 B/op	       5 allocs/op
BenchmarkBeego_GithubParam       	  500000	      3291 ns/op	     368 B/op	       4 allocs/op
BenchmarkBone_GithubParam        	  100000	     20345 ns/op	    1760 B/op	      18 allocs/op
BenchmarkDenco_GithubParam       	 1000000	      1003 ns/op	     128 B/op	       1 allocs/op
BenchmarkGin_GithubParam         	 3000000	       754 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_GithubParam  	  300000	      6218 ns/op	     712 B/op	       9 allocs/op
BenchmarkGoJsonRest_GithubParam  	  500000	      7723 ns/op	     713 B/op	      14 allocs/op
BenchmarkGoRestful_GithubParam   	   20000	     58844 ns/op	    2360 B/op	      21 allocs/op
BenchmarkGorillaMux_GithubParam  	   50000	     26666 ns/op	    1088 B/op	      11 allocs/op
BenchmarkHttpRouter_GithubParam  	 2000000	       809 ns/op	      96 B/op	       1 allocs/op
BenchmarkHttpTreeMux_GithubParam 	  500000	      3684 ns/op	     384 B/op	       4 allocs/op
BenchmarkKocha_GithubParam       	 1000000	      2233 ns/op	     128 B/op	       5 allocs/op
BenchmarkLARS_GithubParam        	 3000000	       711 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_GithubParam     	  200000	      9391 ns/op	    1040 B/op	       9 allocs/op
BenchmarkMartini_GithubParam     	   50000	     43258 ns/op	    1152 B/op	      11 allocs/op
BenchmarkPat_GithubParam         	  100000	     21025 ns/op	    2464 B/op	      48 allocs/op
BenchmarkPossum_GithubParam      	 1000000	      3304 ns/op	     560 B/op	       6 allocs/op
BenchmarkR2router_GithubParam    	 1000000	      2581 ns/op	     432 B/op	       5 allocs/op
BenchmarkRevel_GithubParam       	  100000	     25806 ns/op	    1904 B/op	      33 allocs/op
BenchmarkTigerTonic_GithubParam  	  100000	     13644 ns/op	    1440 B/op	      24 allocs/op
BenchmarkTraffic_GithubParam     	   50000	     40143 ns/op	    5992 B/op	      52 allocs/op
BenchmarkVulcan_GithubParam      	  500000	      3701 ns/op	      98 B/op	       3 allocs/op
```

```go
BenchmarkNoypi_GithubAll          	   10000	    134878 ns/op	    6496 B/op	     203 allocs/op
BenchmarkAce_GithubAll            	   10000	    163377 ns/op	   13792 B/op	     167 allocs/op
BenchmarkBear_GithubAll           	    3000	    676396 ns/op	   86448 B/op	     943 allocs/op
BenchmarkBeego_GithubAll          	    2000	   1053655 ns/op	   74706 B/op	     812 allocs/op
BenchmarkBone_GithubAll           	     100	  13634012 ns/op	  698784 B/op	    8453 allocs/op
BenchmarkDenco_GithubAll          	   10000	    166776 ns/op	   20224 B/op	     167 allocs/op
BenchmarkGin_GithubAll            	   20000	     83694 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_GithubAll     	    3000	   1061209 ns/op	  131656 B/op	    1686 allocs/op
BenchmarkGoJsonRest_GithubAll     	    1000	   1651569 ns/op	  134371 B/op	    2737 allocs/op
BenchmarkGoRestful_GithubAll      	     100	  13737609 ns/op	  689672 B/op	    4519 allocs/op
BenchmarkGorillaMux_GithubAll     	     100	  18141449 ns/op	  211840 B/op	    2272 allocs/op
BenchmarkHttpRouter_GithubAll     	   10000	    115779 ns/op	   13792 B/op	     167 allocs/op
BenchmarkHttpTreeMux_GithubAll    	    5000	    475877 ns/op	   65856 B/op	     671 allocs/op
BenchmarkKocha_GithubAll          	    5000	    422840 ns/op	   23304 B/op	     843 allocs/op
BenchmarkLARS_GithubAll           	   10000	    120873 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_GithubAll        	    2000	   1185790 ns/op	  200946 B/op	    1797 allocs/op
BenchmarkMartini_GithubAll        	     100	  14165267 ns/op	  226552 B/op	    2325 allocs/op
BenchmarkPat_GithubAll            	     200	  12070971 ns/op	 1499568 B/op	   27435 allocs/op
BenchmarkPossum_GithubAll         	    3000	    681104 ns/op	   84448 B/op	     609 allocs/op
BenchmarkR2router_GithubAll       	    3000	    422528 ns/op	   77328 B/op	     979 allocs/op
BenchmarkRevel_GithubAll          	     500	   3135778 ns/op	  369904 B/op	    6527 allocs/op
BenchmarkTigerTonic_GithubAll     	    1000	   1903590 ns/op	  239104 B/op	    5374 allocs/op
BenchmarkTraffic_GithubAll        	     100	  16829576 ns/op	 2659329 B/op	   21848 allocs/op
BenchmarkVulcan_GithubAll         	    3000	    477350 ns/op	   19894 B/op	     609 allocs/op
```

```go
BenchmarkNoypi_GPlusStatic        	 5000000	       466 ns/op	      32 B/op	       1 allocs/op
BenchmarkAce_GPlusStatic          	 3000000	       469 ns/op	       0 B/op	       0 allocs/op
BenchmarkBear_GPlusStatic         	 1000000	      1174 ns/op	     104 B/op	       3 allocs/op
BenchmarkBeego_GPlusStatic        	 1000000	      2413 ns/op	     368 B/op	       4 allocs/op
BenchmarkBone_GPlusStatic         	 3000000	       415 ns/op	      32 B/op	       1 allocs/op
BenchmarkDenco_GPlusStatic        	20000000	        86.9 ns/op	       0 B/op	       0 allocs/op
BenchmarkGin_GPlusStatic          	 5000000	       273 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_GPlusStatic   	 1000000	      2098 ns/op	     280 B/op	       5 allocs/op
BenchmarkGoJsonRest_GPlusStatic   	 1000000	      3218 ns/op	     329 B/op	      11 allocs/op
BenchmarkGoRestful_GPlusStatic    	  100000	     15578 ns/op	    1976 B/op	      20 allocs/op
BenchmarkGorillaMux_GPlusStatic   	  500000	      3683 ns/op	     736 B/op	      10 allocs/op
BenchmarkHttpRouter_GPlusStatic   	20000000	        78.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkHttpTreeMux_GPlusStatic  	20000000	       111 ns/op	       0 B/op	       0 allocs/op
BenchmarkKocha_GPlusStatic        	20000000	       101 ns/op	       0 B/op	       0 allocs/op
BenchmarkLARS_GPlusStatic         	10000000	       219 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_GPlusStatic      	  300000	      6514 ns/op	     752 B/op	       8 allocs/op
BenchmarkMartini_GPlusStatic      	  100000	     14548 ns/op	     768 B/op	       9 allocs/op
BenchmarkPat_GPlusStatic          	 3000000	       581 ns/op	      96 B/op	       2 allocs/op
BenchmarkPossum_GPlusStatic       	 1000000	      2057 ns/op	     416 B/op	       3 allocs/op
BenchmarkR2router_GPlusStatic     	 2000000	       872 ns/op	     144 B/op	       4 allocs/op
BenchmarkRevel_GPlusStatic        	  200000	     15709 ns/op	    1392 B/op	      28 allocs/op
BenchmarkTigerTonic_GPlusStatic   	 2000000	       651 ns/op	      32 B/op	       1 allocs/op
BenchmarkTraffic_GPlusStatic      	  300000	      6631 ns/op	    1192 B/op	      15 allocs/op
BenchmarkVulcan_GPlusStatic       	 1000000	      1136 ns/op	      98 B/op	       3 allocs/op
```

```go
BenchmarkNoypi_GPlusParam         	 3000000	       435 ns/op	      32 B/op	       1 allocs/op
BenchmarkAce_GPlusParam           	 2000000	       947 ns/op	      64 B/op	       1 allocs/op
BenchmarkBear_GPlusParam          	 1000000	      3121 ns/op	     480 B/op	       5 allocs/op
BenchmarkBeego_GPlusParam         	 1000000	      2677 ns/op	     368 B/op	       4 allocs/op
BenchmarkBone_GPlusParam          	 1000000	      2914 ns/op	     688 B/op	       5 allocs/op
BenchmarkDenco_GPlusParam         	 3000000	       470 ns/op	      64 B/op	       1 allocs/op
BenchmarkGin_GPlusParam           	10000000	       244 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_GPlusParam    	 1000000	      2856 ns/op	     648 B/op	       8 allocs/op
BenchmarkGoJsonRest_GPlusParam    	  500000	      4417 ns/op	     649 B/op	      13 allocs/op
BenchmarkGoRestful_GPlusParam     	  100000	     22371 ns/op	    2296 B/op	      21 allocs/op
BenchmarkGorillaMux_GPlusParam    	  200000	     10031 ns/op	    1056 B/op	      11 allocs/op
BenchmarkHttpRouter_GPlusParam    	 5000000	       403 ns/op	      64 B/op	       1 allocs/op
BenchmarkHttpTreeMux_GPlusParam   	 1000000	      1427 ns/op	     352 B/op	       3 allocs/op
BenchmarkKocha_GPlusParam         	 2000000	       989 ns/op	      56 B/op	       3 allocs/op
BenchmarkLARS_GPlusParam          	 3000000	       383 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_GPlusParam       	  500000	      4970 ns/op	    1040 B/op	       9 allocs/op
BenchmarkMartini_GPlusParam       	  100000	     13946 ns/op	    1072 B/op	      10 allocs/op
BenchmarkPat_GPlusParam           	  500000	      5468 ns/op	     688 B/op	      12 allocs/op
BenchmarkPossum_GPlusParam        	  500000	      4920 ns/op	     560 B/op	       6 allocs/op
BenchmarkR2router_GPlusParam      	 1000000	      1709 ns/op	     432 B/op	       5 allocs/op
BenchmarkRevel_GPlusParam         	  100000	     14778 ns/op	    1824 B/op	      31 allocs/op
BenchmarkTigerTonic_GPlusParam    	  300000	      7893 ns/op	    1056 B/op	      17 allocs/op
BenchmarkTraffic_GPlusParam       	  100000	     18247 ns/op	    1976 B/op	      21 allocs/op
BenchmarkVulcan_GPlusParam        	  500000	      2649 ns/op	      98 B/op	       3 allocs/op
```

```go
BenchmarkNoypi_GPlus2Params       	 3000000	       523 ns/op	      32 B/op	       1 allocs/op
BenchmarkAce_GPlus2Params         	 2000000	       733 ns/op	      64 B/op	       1 allocs/op
BenchmarkBear_GPlus2Params        	 1000000	      4072 ns/op	     496 B/op	       5 allocs/op
BenchmarkBeego_GPlus2Params       	  300000	      4504 ns/op	     368 B/op	       4 allocs/op
BenchmarkBone_GPlus2Params        	  200000	      9544 ns/op	    1040 B/op	       9 allocs/op
BenchmarkDenco_GPlus2Params       	 2000000	       663 ns/op	      64 B/op	       1 allocs/op
BenchmarkGin_GPlus2Params         	 5000000	       501 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_GPlus2Params  	  300000	      5982 ns/op	     712 B/op	       9 allocs/op
BenchmarkGoJsonRest_GPlus2Params  	  200000	      5443 ns/op	     713 B/op	      14 allocs/op
BenchmarkGoRestful_GPlus2Params   	  100000	     15048 ns/op	    2360 B/op	      21 allocs/op
BenchmarkGorillaMux_GPlus2Params  	  100000	     19374 ns/op	    1088 B/op	      11 allocs/op
BenchmarkHttpRouter_GPlus2Params  	 3000000	       632 ns/op	      64 B/op	       1 allocs/op
BenchmarkHttpTreeMux_GPlus2Params 	 1000000	      2417 ns/op	     384 B/op	       4 allocs/op
BenchmarkKocha_GPlus2Params       	 1000000	      1176 ns/op	     128 B/op	       5 allocs/op
BenchmarkLARS_GPlus2Params        	 5000000	       316 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_GPlus2Params     	  500000	      6606 ns/op	    1040 B/op	       9 allocs/op
BenchmarkMartini_GPlus2Params     	   30000	     48962 ns/op	    1200 B/op	      13 allocs/op
BenchmarkPat_GPlus2Params         	  100000	     14139 ns/op	    2256 B/op	      34 allocs/op
BenchmarkPossum_GPlus2Params      	 1000000	      2930 ns/op	     560 B/op	       6 allocs/op
BenchmarkR2router_GPlus2Params    	 1000000	      2343 ns/op	     432 B/op	       5 allocs/op
BenchmarkRevel_GPlus2Params       	  100000	     25189 ns/op	    1920 B/op	      33 allocs/op
BenchmarkTigerTonic_GPlus2Params  	  100000	     12078 ns/op	    1488 B/op	      24 allocs/op
BenchmarkTraffic_GPlus2Params     	   50000	     25708 ns/op	    3272 B/op	      31 allocs/op
BenchmarkVulcan_GPlus2Params      	 1000000	      2462 ns/op	      98 B/op	       3 allocs/op
```

```go
BenchmarkNoypi_GPlusAll      	  300000	      8850 ns/op	     416 B/op	      13 allocs/op
BenchmarkAce_GPlusAll        	  200000	     11613 ns/op	     640 B/op	      11 allocs/op
BenchmarkBear_GPlusAll       	   50000	     33484 ns/op	    5488 B/op	      61 allocs/op
BenchmarkBeego_GPlusAll      	   50000	     41631 ns/op	    4784 B/op	      52 allocs/op
BenchmarkBone_GPlusAll       	   20000	     91380 ns/op	   10336 B/op	      98 allocs/op
BenchmarkGin_GPlusAll        	  300000	      4154 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_GPlusAll 	   30000	     51785 ns/op	    8040 B/op	     103 allocs/op
BenchmarkGoJsonRest_GPlusAll 	   30000	     58953 ns/op	    8117 B/op	     170 allocs/op
BenchmarkGoRestful_GPlusAll  	   10000	    220125 ns/op	   32024 B/op	     275 allocs/op
BenchmarkGorillaMux_GPlusAll 	   10000	    154040 ns/op	   13296 B/op	     142 allocs/op
BenchmarkHttpRouter_GPlusAll 	  300000	      5721 ns/op	     640 B/op	      11 allocs/op
BenchmarkLARS_GPlusAll       	  500000	      3782 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_GPlusAll    	   20000	     77088 ns/op	   12944 B/op	     115 allocs/op
BenchmarkMartini_GPlusAll    	   10000	    251312 ns/op	   14016 B/op	     145 allocs/op
BenchmarkPat_GPlusAll        	   10000	    108308 ns/op	   16576 B/op	     298 allocs/op
BenchmarkPossum_GPlusAll     	   50000	     32332 ns/op	    5408 B/op	      39 allocs/op
BenchmarkR2router_GPlusAll   	   50000	     37780 ns/op	    5040 B/op	      63 allocs/op
BenchmarkRevel_GPlusAll      	   10000	    320962 ns/op	   23216 B/op	     407 allocs/op
BenchmarkTigerTonic_GPlusAll 	   10000	    143742 ns/op	   14512 B/op	     288 allocs/op
BenchmarkTraffic_GPlusAll    	    5000	    387576 ns/op	   37360 B/op	     392 allocs/op
BenchmarkVulcan_GPlusAll     	   50000	     28125 ns/op	    1274 B/op	      39 allocs/op
```

```go
BenchmarkNoypi_ParseStatic        	 3000000	       443 ns/op	      32 B/op	       1 allocs/op
BenchmarkAce_ParseStatic          	 5000000	       285 ns/op	       0 B/op	       0 allocs/op
BenchmarkBear_ParseStatic         	 1000000	      1020 ns/op	     120 B/op	       3 allocs/op
BenchmarkBeego_ParseStatic        	 1000000	      2844 ns/op	     368 B/op	       4 allocs/op
BenchmarkDenco_ParseStatic        	20000000	        99.7 ns/op	       0 B/op	       0 allocs/op
BenchmarkGin_ParseStatic          	10000000	       159 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_ParseStatic   	 1000000	      1845 ns/op	     296 B/op	       5 allocs/op
BenchmarkGoJsonRest_ParseStatic   	 1000000	      2551 ns/op	     329 B/op	      11 allocs/op
BenchmarkGoRestful_ParseStatic    	   50000	     27142 ns/op	    3224 B/op	      22 allocs/op
BenchmarkGorillaMux_ParseStatic   	  200000	      8326 ns/op	     752 B/op	      11 allocs/op
BenchmarkHttpRouter_ParseStatic   	20000000	        85.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkHttpTreeMux_ParseStatic  	10000000	       160 ns/op	       0 B/op	       0 allocs/op
BenchmarkKocha_ParseStatic        	20000000	       114 ns/op	       0 B/op	       0 allocs/op
BenchmarkLARS_ParseStatic         	10000000	       171 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_ParseStatic      	  500000	      4769 ns/op	     752 B/op	       8 allocs/op
BenchmarkMartini_ParseStatic      	  200000	     13591 ns/op	     768 B/op	       9 allocs/op
BenchmarkPat_ParseStatic          	 1000000	      1533 ns/op	     240 B/op	       5 allocs/op
BenchmarkPossum_ParseStatic       	 1000000	      3852 ns/op	     416 B/op	       3 allocs/op
BenchmarkR2router_ParseStatic     	 1000000	      1440 ns/op	     144 B/op	       4 allocs/op
BenchmarkRevel_ParseStatic        	  100000	     20816 ns/op	    1408 B/op	      28 allocs/op
BenchmarkTigerTonic_ParseStatic   	 1000000	      1006 ns/op	      48 B/op	       1 allocs/op
BenchmarkTraffic_ParseStatic      	  100000	     11297 ns/op	    1816 B/op	      20 allocs/op
BenchmarkVulcan_ParseStatic       	 1000000	      1452 ns/op	      98 B/op	       3 allocs/op
```

```go
BenchmarkNoypi_ParseParam         	 5000000	       414 ns/op	      32 B/op	       1 allocs/op
BenchmarkAce_ParseParam           	 2000000	       642 ns/op	      64 B/op	       1 allocs/op
BenchmarkBear_ParseParam          	 1000000	      2416 ns/op	     467 B/op	       5 allocs/op
BenchmarkBeego_ParseParam         	 1000000	      3403 ns/op	     368 B/op	       4 allocs/op
BenchmarkBone_ParseParam          	  500000	      4905 ns/op	     768 B/op	       6 allocs/op
BenchmarkDenco_ParseParam         	 2000000	       857 ns/op	      64 B/op	       1 allocs/op
BenchmarkGin_ParseParam           	 5000000	       319 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_ParseParam    	  500000	      3518 ns/op	     664 B/op	       8 allocs/op
BenchmarkGoJsonRest_ParseParam    	  500000	      3940 ns/op	     649 B/op	      13 allocs/op
BenchmarkGoRestful_ParseParam     	  100000	     31019 ns/op	    3544 B/op	      23 allocs/op
BenchmarkGorillaMux_ParseParam    	  200000	     12259 ns/op	    1088 B/op	      12 allocs/op
BenchmarkHttpRouter_ParseParam    	 3000000	       383 ns/op	      64 B/op	       1 allocs/op
BenchmarkHttpTreeMux_ParseParam   	 1000000	      1578 ns/op	     352 B/op	       3 allocs/op
BenchmarkKocha_ParseParam         	 2000000	       664 ns/op	      56 B/op	       3 allocs/op
BenchmarkLARS_ParseParam          	10000000	       181 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_ParseParam       	  500000	      6016 ns/op	    1040 B/op	       9 allocs/op
BenchmarkMartini_ParseParam       	  100000	     18339 ns/op	    1072 B/op	      10 allocs/op
BenchmarkPat_ParseParam           	  300000	      7191 ns/op	    1120 B/op	      17 allocs/op
BenchmarkPossum_ParseParam        	 1000000	      3476 ns/op	     560 B/op	       6 allocs/op
BenchmarkR2router_ParseParam      	 1000000	      2059 ns/op	     432 B/op	       5 allocs/op
BenchmarkRevel_ParseParam         	  100000	     15951 ns/op	    1824 B/op	      31 allocs/op
BenchmarkTigerTonic_ParseParam    	  300000	      7336 ns/op	    1008 B/op	      17 allocs/op
BenchmarkTraffic_ParseParam       	  200000	     12456 ns/op	    2248 B/op	      23 allocs/op
BenchmarkVulcan_ParseParam        	 1000000	      1442 ns/op	      98 B/op	       3 allocs/op
```

```go
BenchmarkNoypi_Parse2Params       	 3000000	       531 ns/op	      32 B/op	       1 allocs/op
BenchmarkAce_Parse2Params         	 1000000	      1112 ns/op	      64 B/op	       1 allocs/op
BenchmarkBear_Parse2Params        	  500000	      4160 ns/op	     496 B/op	       5 allocs/op
BenchmarkBeego_Parse2Params       	 1000000	      3198 ns/op	     368 B/op	       4 allocs/op
BenchmarkBone_Parse2Params        	 1000000	      5481 ns/op	     720 B/op	       5 allocs/op
BenchmarkDenco_Parse2Params       	 2000000	       596 ns/op	      64 B/op	       1 allocs/op
BenchmarkGin_Parse2Params         	10000000	       233 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_Parse2Params  	  500000	      4745 ns/op	     712 B/op	       9 allocs/op
BenchmarkGoJsonRest_Parse2Params  	  300000	      8089 ns/op	     713 B/op	      14 allocs/op
BenchmarkGoRestful_Parse2Params   	   50000	     44315 ns/op	    6008 B/op	      25 allocs/op
BenchmarkGorillaMux_Parse2Params  	  200000	     11618 ns/op	    1088 B/op	      11 allocs/op
BenchmarkHttpRouter_Parse2Params  	 3000000	       433 ns/op	      64 B/op	       1 allocs/op
BenchmarkHttpTreeMux_Parse2Params 	 1000000	      2146 ns/op	     384 B/op	       4 allocs/op
BenchmarkKocha_Parse2Params       	 1000000	      1155 ns/op	     128 B/op	       5 allocs/op
BenchmarkLARS_Parse2Params        	10000000	       225 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_Parse2Params     	  500000	      7493 ns/op	    1040 B/op	       9 allocs/op
BenchmarkMartini_Parse2Params     	   50000	     25325 ns/op	    1152 B/op	      11 allocs/op
BenchmarkPat_Parse2Params         	  200000	      6545 ns/op	     832 B/op	      17 allocs/op
BenchmarkPossum_Parse2Params      	 1000000	      3372 ns/op	     560 B/op	       6 allocs/op
BenchmarkR2router_Parse2Params    	 1000000	      2209 ns/op	     432 B/op	       5 allocs/op
BenchmarkRevel_Parse2Params       	  100000	     16803 ns/op	    1888 B/op	      33 allocs/op
BenchmarkTigerTonic_Parse2Params  	  200000	     11903 ns/op	    1408 B/op	      24 allocs/op
BenchmarkTraffic_Parse2Params     	  100000	     15725 ns/op	    2040 B/op	      22 allocs/op
BenchmarkVulcan_Parse2Params      	 1000000	      2065 ns/op	      98 B/op	       3 allocs/op
```

```go
BenchmarkNoypi_ParseAll           	  100000	     16158 ns/op	     832 B/op	      26 allocs/op
BenchmarkAce_ParseAll             	  100000	     17558 ns/op	     640 B/op	      16 allocs/op
BenchmarkBear_ParseAll            	   20000	     56201 ns/op	    8928 B/op	     110 allocs/op
BenchmarkBeego_ParseAll           	   20000	     74773 ns/op	    9568 B/op	     104 allocs/op
BenchmarkBone_ParseAll            	   20000	    143160 ns/op	   14160 B/op	     131 allocs/op
BenchmarkDenco_ParseAll           	  200000	     10550 ns/op	     928 B/op	      16 allocs/op
BenchmarkGin_ParseAll             	  200000	      6940 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_ParseAll      	   20000	     81584 ns/op	   13728 B/op	     181 allocs/op
BenchmarkGoJsonRest_ParseAll      	   10000	    100466 ns/op	   13866 B/op	     321 allocs/op
BenchmarkGoRestful_ParseAll       	    3000	   1062409 ns/op	  110928 B/op	     600 allocs/op
BenchmarkGorillaMux_ParseAll      	    3000	    466614 ns/op	   24864 B/op	     292 allocs/op
BenchmarkHttpRouter_ParseAll      	  200000	      7178 ns/op	     640 B/op	      16 allocs/op
BenchmarkHttpTreeMux_ParseAll     	   50000	     31970 ns/op	    5728 B/op	      51 allocs/op
BenchmarkKocha_ParseAll           	  100000	     15870 ns/op	    1112 B/op	      54 allocs/op
BenchmarkLARS_ParseAll            	  200000	      8375 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_ParseAll         	   10000	    236134 ns/op	   24160 B/op	     224 allocs/op
BenchmarkMartini_ParseAll         	    3000	    417316 ns/op	   25072 B/op	     253 allocs/op
BenchmarkPat_ParseAll             	   10000	    111394 ns/op	   17264 B/op	     343 allocs/op
BenchmarkPossum_ParseAll          	   20000	     64472 ns/op	   10816 B/op	      78 allocs/op
BenchmarkR2router_ParseAll        	   20000	     71514 ns/op	    8352 B/op	     120 allocs/op
BenchmarkRevel_ParseAll           	    3000	    554365 ns/op	   43584 B/op	     782 allocs/op
BenchmarkTigerTonic_ParseAll      	   10000	    173981 ns/op	   19728 B/op	     379 allocs/op
BenchmarkTraffic_ParseAll         	   10000	    343296 ns/op	   57776 B/op	     642 allocs/op
BenchmarkVulcan_ParseAll          	   30000	     46687 ns/op	    2548 B/op	      78 allocs/op
```

```go
BenchmarkNoypi_StaticAll        	   20000	     88988 ns/op	    5024 B/op	     157 allocs/op
BenchmarkGin_StaticAll          	   30000	     54137 ns/op	       0 B/op	       0 allocs/op
BenchmarkAce_StaticAll          	   20000	     71977 ns/op	       0 B/op	       0 allocs/op
BenchmarkHttpServeMux_StaticAll 	    1000	   1813848 ns/op	      96 B/op	       8 allocs/op
BenchmarkBeego_StaticAll        	    5000	    513440 ns/op	   57777 B/op	     628 allocs/op
BenchmarkBear_StaticAll         	   10000	    218861 ns/op	   20336 B/op	     461 allocs/op
BenchmarkBone_StaticAll         	   10000	    267452 ns/op	       0 B/op	       0 allocs/op
BenchmarkDenco_StaticAll        	   50000	     34190 ns/op	       0 B/op	       0 allocs/op
BenchmarkGocraftWeb_StaticAll   	   10000	    322353 ns/op	   46440 B/op	     785 allocs/op
BenchmarkGoJsonRest_StaticAll   	    3000	    552106 ns/op	   51653 B/op	    1727 allocs/op
BenchmarkGoRestful_StaticAll    	     300	   6007121 ns/op	  314936 B/op	    3144 allocs/op
BenchmarkGorillaMux_StaticAll   	     300	   4868498 ns/op	  115648 B/op	    1578 allocs/op
BenchmarkHttpRouter_StaticAll   	   30000	     59631 ns/op	       0 B/op	       0 allocs/op
BenchmarkHttpTreeMux_StaticAll  	   30000	     36165 ns/op	       0 B/op	       0 allocs/op
BenchmarkKocha_StaticAll        	   50000	     50444 ns/op	       0 B/op	       0 allocs/op
BenchmarkLARS_StaticAll         	   20000	     68296 ns/op	       0 B/op	       0 allocs/op
BenchmarkMacaron_StaticAll      	    2000	    871504 ns/op	  118065 B/op	    1256 allocs/op
BenchmarkMartini_StaticAll      	     200	   6827889 ns/op	  125444 B/op	    1717 allocs/op
BenchmarkPat_StaticAll          	     500	   2861068 ns/op	  533904 B/op	   11123 allocs/op
BenchmarkPossum_StaticAll       	    5000	    504786 ns/op	   65312 B/op	     471 allocs/op
BenchmarkR2router_StaticAll     	    5000	    220791 ns/op	   22608 B/op	     628 allocs/op
BenchmarkRevel_StaticAll        	     500	   2795530 ns/op	  223360 B/op	    4396 allocs/op
BenchmarkTigerTonic_StaticAll   	   10000	    133811 ns/op	    7504 B/op	     157 allocs/op
BenchmarkTraffic_StaticAll      	     300	   4127822 ns/op	  729736 B/op	   14287 allocs/op
BenchmarkVulcan_StaticAll       	    5000	    368666 ns/op	   15386 B/op	     471 allocs/op
```
`id:000000,sig:11,src:000434,op:havoc,rep:8`
```
#0  0x000000000041186a in ReenterFunctionLevel (F=0x93c440) at cc65/symtab.c:306
#1  0x000000000046a11d in NewFunc (Func=0x93c380) at cc65/function.c:408
#2  0x00000000004500b5 in Parse () at cc65/compile.c:294
#3  Compile (FileName=<optimized out>) at cc65/compile.c:403
#4  0x0000000000405398 in main (argc=<optimized out>, argv=<optimized out>) at cc65/main.c:1052
```

`id:000001,sig:11,src:000763,op:havoc,rep:8`
```
#0  0x0000000000411855 in ReenterFunctionLevel (F=0x20bb5b0) at cc65/symtab.c:303
#1  0x000000000046a11d in NewFunc (Func=0x20bc710) at cc65/function.c:408
#2  0x00000000004500b5 in Parse () at cc65/compile.c:294
#3  Compile (FileName=<optimized out>) at cc65/compile.c:403
#4  0x0000000000405398 in main (argc=<optimized out>, argv=<optimized out>) at cc65/main.c:1052
```

`id:000054,sig:06,src:001513,op:arith8,pos:13,val:-15`
```
#0  __GI_raise (sig=sig@entry=6) at ../sysdeps/unix/sysv/linux/raise.c:51
#1  0x00007f48beb073fa in __GI_abort () at abort.c:89
#2  0x0000000000486e12 in Internal (Format=0x49f2d0 "Code generation messed up: StackPtr is %d, should be %d") at cc65/error.c:161
#3  0x0000000000477246 in ExprWithCheck (Func=<optimized out>, Expr=<optimized out>) at cc65/expr.c:119
#4  0x000000000046b823 in ShiftExpr (Expr=0x7ffccb0531b0) at cc65/shiftexpr.c:77
#5  0x000000000048239d in ExprWithCheck (Func=0x46b7e0 <ShiftExpr>, Expr=0x7ffccb0531b0) at cc65/expr.c:110
#6  hie_compare (Ops=0x49f270 <hie6.hie6_ops>, Expr=0x7ffccb0531b0, hienext=0x46b7e0 <ShiftExpr>) at cc65/expr.c:2097
#7  0x000000000048239d in ExprWithCheck (Func=0x483990 <hie6>, Expr=0x7ffccb0531b0) at cc65/expr.c:110
#8  hie_compare (Ops=0x49f240 <hie5.hie5_ops>, Expr=0x7ffccb0531b0, hienext=0x483990 <hie6>) at cc65/expr.c:2097
#9  0x00000000004810f9 in ExprWithCheck (Func=0x0, Expr=0x7ffccb0531b0) at cc65/expr.c:110
#10 hie_internal (Ops=0x49f220 <hie4.hie4_ops>, Expr=0x7ffccb0531b0, hienext=0x0, UsedGen=0x7ffccb052d84) at cc65/expr.c:1877
#11 0x00000000004822fe in hie4 (Expr=0x7ffccb0526d0) at cc65/expr.c:2912
#12 0x00000000004810f9 in ExprWithCheck (Func=0x0, Expr=0x7ffccb0531b0) at cc65/expr.c:110
#13 hie_internal (Ops=0x49f200 <hie3.hie3_ops>, Expr=0x7ffccb0531b0, hienext=0x0, UsedGen=0x7ffccb052e74) at cc65/expr.c:1877
#14 0x00000000004822be in hie3 (Expr=0x7ffccb0526d0) at cc65/expr.c:2926
#15 0x00000000004810f9 in ExprWithCheck (Func=0x0, Expr=0x7ffccb0531b0) at cc65/expr.c:110
#16 hie_internal (Ops=0x49f1e0 <hie2.hie2_ops>, Expr=0x7ffccb0531b0, hienext=0x0, UsedGen=0x7ffccb052fb4) at cc65/expr.c:1877
#17 0x0000000000483a26 in hie2 (Expr=0x7ffccb0531b0) at cc65/expr.c:2940
#18 ExprWithCheck (Expr=0x7ffccb0531b0, Func=<optimized out>) at cc65/expr.c:110
#19 hieAnd (Expr=0x7ffccb0531b0, TrueLab=1, BoolOp=0x7ffccb0530a8) at cc65/expr.c:2997
#20 0x000000000047e932 in hieOr (Expr=0x7ffccb0531b0) at cc65/expr.c:3063
#21 ExprWithCheck (Func=<optimized out>, Expr=<optimized out>) at cc65/expr.c:110
#22 hieQuest (Expr=<optimized out>) at cc65/expr.c:3140
#23 hie1 (Expr=0x7ffccb0531b0) at cc65/expr.c:3514
#24 0x0000000000480a68 in ExprWithCheck (Func=0x0, Expr=0x7ffccb0531b0) at cc65/expr.c:110
#25 ConstAbsIntExpr (Func=0x0, Expr=0x7ffccb0531b0) at cc65/expr.c:3653
#26 0x0000000000424861 in Declarator (Spec=<optimized out>, D=<optimized out>, Mode=<optimized out>) at cc65/declare.c:1509
#27 0x0000000000423879 in ParseDecl (Spec=0x7ffccb053528, D=0x7ffccb0532e8, Mode=(unknown: 3406112464)) at cc65/declare.c:1584
#28 0x000000000045028d in Parse () at cc65/compile.c:137
#29 Compile (FileName=<optimized out>) at cc65/compile.c:403
#30 0x0000000000405398 in main (argc=<optimized out>, argv=<optimized out>) at cc65/main.c:1052
```

`id:000209,sig:11,src:001099,op:arith8,pos:14,val:-17`
```
#0  F_IsVariadic (F=0x0) at cc65/function.c:192
#1  0x000000000047b928 in Primary (E=0x7fffdc939d70) at cc65/expr.c:740
#2  hie11 (Expr=<optimized out>) at cc65/expr.c:1288
#3  hie10 (Expr=0x7fffdc939d70) at cc65/expr.c:1845
#4  0x00000000004810f9 in ExprWithCheck (Func=0x6ae690 <__afl_area_initial>, Expr=0x7fffdc939d70) at cc65/expr.c:110
#5  hie_internal (Ops=0x49f1a0 <hie9.hie9_ops>, Expr=0x7fffdc939d70, hienext=0x6ae690 <__afl_area_initial>, UsedGen=0x7fffdc938950) at cc65/expr.c:1877
#6  0x000000000047bef6 in hie9 (Expr=0x7fffdc939d70) at cc65/expr.c:2438
#7  ExprWithCheck (Expr=0x7fffdc939d70, Func=<optimized out>) at cc65/expr.c:110
#8  hie8 (Expr=0x7fffdc939d70) at cc65/expr.c:2863
#9  0x00000000004771a4 in ExprWithCheck (Func=0xfffffffffffffffc, Expr=0x0) at cc65/expr.c:110
#10 0x000000000046b823 in ShiftExpr (Expr=0x7fffdc939d70) at cc65/shiftexpr.c:77
#11 0x000000000048239d in ExprWithCheck (Func=0x46b7e0 <ShiftExpr>, Expr=0x7fffdc939d70) at cc65/expr.c:110
#12 hie_compare (Ops=0x49f270 <hie6.hie6_ops>, Expr=0x7fffdc939d70, hienext=0x46b7e0 <ShiftExpr>) at cc65/expr.c:2097
#13 0x000000000048239d in ExprWithCheck (Func=0x483990 <hie6>, Expr=0x7fffdc939d70) at cc65/expr.c:110
#14 hie_compare (Ops=0x49f240 <hie5.hie5_ops>, Expr=0x7fffdc939d70, hienext=0x483990 <hie6>) at cc65/expr.c:2097
#15 0x00000000004810f9 in ExprWithCheck (Func=0x6ae690 <__afl_area_initial>, Expr=0x7fffdc939d70) at cc65/expr.c:110
#16 hie_internal (Ops=0x49f220 <hie4.hie4_ops>, Expr=0x7fffdc939d70, hienext=0x6ae690 <__afl_area_initial>, UsedGen=0x7fffdc938d74) at cc65/expr.c:1877
#17 0x00000000004822fe in hie4 (Expr=0x15) at cc65/expr.c:2912
#18 0x00000000004810f9 in ExprWithCheck (Func=0x6ae690 <__afl_area_initial>, Expr=0x7fffdc939d70) at cc65/expr.c:110
#19 hie_internal (Ops=0x49f200 <hie3.hie3_ops>, Expr=0x7fffdc939d70, hienext=0x6ae690 <__afl_area_initial>, UsedGen=0x7fffdc938e64) at cc65/expr.c:1877
#20 0x00000000004822be in hie3 (Expr=0x15) at cc65/expr.c:2926
#21 0x00000000004810f9 in ExprWithCheck (Func=0x6ae690 <__afl_area_initial>, Expr=0x7fffdc939d70) at cc65/expr.c:110
#22 hie_internal (Ops=0x49f1e0 <hie2.hie2_ops>, Expr=0x7fffdc939d70, hienext=0x6ae690 <__afl_area_initial>, UsedGen=0x7fffdc938fa4) at cc65/expr.c:1877
#23 0x0000000000483a26 in hie2 (Expr=0x7fffdc939d70) at cc65/expr.c:2940
#24 ExprWithCheck (Expr=0x7fffdc939d70, Func=<optimized out>) at cc65/expr.c:110
#25 hieAnd (Expr=0x7fffdc939d70, TrueLab=4, BoolOp=0x7fffdc939098) at cc65/expr.c:2997
#26 0x000000000047e932 in hieOr (Expr=0x7fffdc939d70) at cc65/expr.c:3063
#27 ExprWithCheck (Func=<optimized out>, Expr=<optimized out>) at cc65/expr.c:110
#28 hieQuest (Expr=<optimized out>) at cc65/expr.c:3140
#29 hie1 (Expr=0x7fffdc939d70) at cc65/expr.c:3514
#30 0x0000000000478409 in hie0 (Expr=<optimized out>) at cc65/expr.c:3574
#31 Primary (E=<optimized out>) at cc65/expr.c:673
#32 hie11 (Expr=<optimized out>) at cc65/expr.c:1288
#33 hie10 (Expr=<optimized out>) at cc65/expr.c:1845
#34 0x00000000004810f9 in ExprWithCheck (Func=0x6ae690 <__afl_area_initial>, Expr=0x7fffdc939d70) at cc65/expr.c:110
#35 hie_internal (Ops=0x49f1a0 <hie9.hie9_ops>, Expr=0x7fffdc939d70, hienext=0x6ae690 <__afl_area_initial>, UsedGen=0x7fffdc939520) at cc65/expr.c:1877
#36 0x000000000047bef6 in hie9 (Expr=0x7fffdc939d70) at cc65/expr.c:2438
#37 ExprWithCheck (Expr=0x7fffdc939d70, Func=<optimized out>) at cc65/expr.c:110
#38 hie8 (Expr=0x7fffdc939d70) at cc65/expr.c:2863
#39 0x00000000004771a4 in ExprWithCheck (Func=0xfffffffffffffffc, Expr=0x0) at cc65/expr.c:110
#40 0x000000000046b823 in ShiftExpr (Expr=0x7fffdc939d70) at cc65/shiftexpr.c:77
#41 0x000000000048239d in ExprWithCheck (Func=0x46b7e0 <ShiftExpr>, Expr=0x7fffdc939d70) at cc65/expr.c:110
#42 hie_compare (Ops=0x49f270 <hie6.hie6_ops>, Expr=0x7fffdc939d70, hienext=0x46b7e0 <ShiftExpr>) at cc65/expr.c:2097
#43 0x000000000048239d in ExprWithCheck (Func=0x483990 <hie6>, Expr=0x7fffdc939d70) at cc65/expr.c:110
#44 hie_compare (Ops=0x49f240 <hie5.hie5_ops>, Expr=0x7fffdc939d70, hienext=0x483990 <hie6>) at cc65/expr.c:2097
#45 0x00000000004810f9 in ExprWithCheck (Func=0x6ae690 <__afl_area_initial>, Expr=0x7fffdc939d70) at cc65/expr.c:110
#46 hie_internal (Ops=0x49f220 <hie4.hie4_ops>, Expr=0x7fffdc939d70, hienext=0x6ae690 <__afl_area_initial>, UsedGen=0x7fffdc939944) at cc65/expr.c:1877
#47 0x00000000004822fe in hie4 (Expr=0x15) at cc65/expr.c:2912
#48 0x00000000004810f9 in ExprWithCheck (Func=0x6ae690 <__afl_area_initial>, Expr=0x7fffdc939d70) at cc65/expr.c:110
#49 hie_internal (Ops=0x49f200 <hie3.hie3_ops>, Expr=0x7fffdc939d70, hienext=0x6ae690 <__afl_area_initial>, UsedGen=0x7fffdc939a34) at cc65/expr.c:1877
#50 0x00000000004822be in hie3 (Expr=0x15) at cc65/expr.c:2926
#51 0x00000000004810f9 in ExprWithCheck (Func=0x6ae690 <__afl_area_initial>, Expr=0x7fffdc939d70) at cc65/expr.c:110
#52 hie_internal (Ops=0x49f1e0 <hie2.hie2_ops>, Expr=0x7fffdc939d70, hienext=0x6ae690 <__afl_area_initial>, UsedGen=0x7fffdc939b74) at cc65/expr.c:1877
#53 0x0000000000483a26 in hie2 (Expr=0x7fffdc939d70) at cc65/expr.c:2940
#54 ExprWithCheck (Expr=0x7fffdc939d70, Func=<optimized out>) at cc65/expr.c:110
#55 hieAnd (Expr=0x7fffdc939d70, TrueLab=1, BoolOp=0x7fffdc939c68) at cc65/expr.c:2997
#56 0x000000000047e932 in hieOr (Expr=0x7fffdc939d70) at cc65/expr.c:3063
#57 ExprWithCheck (Func=<optimized out>, Expr=<optimized out>) at cc65/expr.c:110
#58 hieQuest (Expr=<optimized out>) at cc65/expr.c:3140
#59 hie1 (Expr=0x7fffdc939d70) at cc65/expr.c:3514
#60 0x0000000000480a68 in ExprWithCheck (Func=0xfffffffffffffffc, Expr=0x7fffdc939d70) at cc65/expr.c:110
#61 ConstAbsIntExpr (Func=0xfffffffffffffffc, Expr=0x7fffdc939d70) at cc65/expr.c:3653
#62 0x0000000000424861 in Declarator (Spec=<optimized out>, D=<optimized out>, Mode=<optimized out>) at cc65/declare.c:1509
#63 0x0000000000423879 in ParseDecl (Spec=0x7fffdc93a098, D=0x7fffdc939e58, Mode=(DM_NO_IDENT | unknown: 20)) at cc65/declare.c:1584
#64 0x000000000042856f in ParseAnsiParamList (F=<optimized out>) at cc65/declare.c:1266
#65 0x0000000000424a4a in ParseFuncDecl () at cc65/declare.c:1352
#66 Declarator (Spec=<optimized out>, D=<optimized out>, Mode=<optimized out>) at cc65/declare.c:1466
#67 0x0000000000423879 in ParseDecl (Spec=0x7fffdc93a5f8, D=0x7fffdc93a3b8, Mode=(DM_NO_IDENT | unknown: 20)) at cc65/declare.c:1584
#68 0x000000000042856f in ParseAnsiParamList (F=<optimized out>) at cc65/declare.c:1266
#69 0x0000000000424a4a in ParseFuncDecl () at cc65/declare.c:1352
#70 Declarator (Spec=<optimized out>, D=<optimized out>, Mode=<optimized out>) at cc65/declare.c:1466
#71 0x0000000000423879 in ParseDecl (Spec=0x7fffdc93aba8, D=0x7fffdc93a968, Mode=(DM_NO_IDENT | unknown: 20)) at cc65/declare.c:1584
#72 0x000000000045028d in Parse () at cc65/compile.c:137
#73 Compile (FileName=<optimized out>) at cc65/compile.c:403
#74 0x0000000000405398 in main (argc=<optimized out>, argv=<optimized out>) at cc65/main.c:1052
```

`id:000279,sig:11,src:003987,op:havoc,rep:16`
```
#0  0x0000000000477604 in hie10 (Expr=0x7ffd3e21b408) at cc65/expr.c:1723
#1  0x00000000004777ae in UnaryOp (Expr=0x7ffd3e21b408) at cc65/expr.c:1682
#2  hie10 (Expr=0x7ffd3e21b408) at cc65/expr.c:1739
#3  0x00000000004777ae in UnaryOp (Expr=0x7ffd3e21b408) at cc65/expr.c:1682
#4  hie10 (Expr=0x7ffd3e21b408) at cc65/expr.c:1739
#5  0x00000000004777ae in UnaryOp (Expr=0x7ffd3e21b408) at cc65/expr.c:1682
#6  hie10 (Expr=0x7ffd3e21b408) at cc65/expr.c:1739
#7  0x00000000004777ae in UnaryOp (Expr=0x7ffd3e21b408) at cc65/expr.c:1682
#8  hie10 (Expr=0x7ffd3e21b408) at cc65/expr.c:1739
#9  0x00000000004777ae in UnaryOp (Expr=0x7ffd3e21b408) at cc65/expr.c:1682
#10 hie10 (Expr=0x7ffd3e21b408) at cc65/expr.c:1739
#11 0x00000000004777ae in UnaryOp (Expr=0x7ffd3e21b408) at cc65/expr.c:1682
#12 hie10 (Expr=0x7ffd3e21b408) at cc65/expr.c:1739
#13 0x00000000004777ae in UnaryOp (Expr=0x7ffd3e21b408) at cc65/expr.c:1682
#14 hie10 (Expr=0x7ffd3e21b408) at cc65/expr.c:1739
#15 0x00000000004777ae in UnaryOp (Expr=0x7ffd3e21b408) at cc65/expr.c:1682
#16 hie10 (Expr=0x7ffd3e21b408) at cc65/expr.c:1739
#17 0x00000000004777ae in UnaryOp (Expr=0x7ffd3e21b408) at cc65/expr.c:1682
#18 hie10 (Expr=0x7ffd3e21b408) at cc65/expr.c:1739
#19 0x00000000004777ae in UnaryOp (Expr=0x7ffd3e21b408) at cc65/expr.c:1682
#20 hie10 (Expr=0x7ffd3e21b408) at cc65/expr.c:1739
```



`id:000359,sig:11,src:002548,op:havoc,rep:8`
```
#0  0x000000000042ce42 in SkipWhite () at cc65/scanner.c:195
#1  NextToken () at cc65/scanner.c:708
#2  0x00000000004783a6 in Primary (E=0x7ffdeb29ff80) at cc65/expr.c:672
#3  hie11 (Expr=<optimized out>) at cc65/expr.c:1288
#4  hie10 (Expr=0x7ffdeb29ff80) at cc65/expr.c:1845
#5  0x00000000004810f9 in ExprWithCheck (Func=0x6ae690 <__afl_area_initial>, Expr=0x7ffdeb29ff80) at cc65/expr.c:110
#6  hie_internal (Ops=0x49f1a0 <hie9.hie9_ops>, Expr=0x7ffdeb29ff80, hienext=0x6ae690 <__afl_area_initial>, UsedGen=0x7ffdeb19f410) at cc65/expr.c:1877
#7  0x000000000047bef6 in hie9 (Expr=0x7ffdeb29ff80) at cc65/expr.c:2438
#8  ExprWithCheck (Expr=0x7ffdeb29ff80, Func=<optimized out>) at cc65/expr.c:110
#9  hie8 (Expr=0x7ffdeb29ff80) at cc65/expr.c:2863
#10 0x00000000004771a4 in ExprWithCheck (Func=0x5d28, Expr=0x28) at cc65/expr.c:110
#11 0x000000000046b823 in ShiftExpr (Expr=0x7ffdeb29ff80) at cc65/shiftexpr.c:77
#12 0x000000000048239d in ExprWithCheck (Func=0x46b7e0 <ShiftExpr>, Expr=0x7ffdeb29ff80) at cc65/expr.c:110
#13 hie_compare (Ops=0x49f270 <hie6.hie6_ops>, Expr=0x7ffdeb29ff80, hienext=0x46b7e0 <ShiftExpr>) at cc65/expr.c:2097
#14 0x000000000048239d in ExprWithCheck (Func=0x483990 <hie6>, Expr=0x7ffdeb29ff80) at cc65/expr.c:110
#15 hie_compare (Ops=0x49f240 <hie5.hie5_ops>, Expr=0x7ffdeb29ff80, hienext=0x483990 <hie6>) at cc65/expr.c:2097
#16 0x00000000004810f9 in ExprWithCheck (Func=0x6ae690 <__afl_area_initial>, Expr=0x7ffdeb29ff80) at cc65/expr.c:110
#17 hie_internal (Ops=0x49f220 <hie4.hie4_ops>, Expr=0x7ffdeb29ff80, hienext=0x6ae690 <__afl_area_initial>, UsedGen=0x7ffdeb19f834) at cc65/expr.c:1877
#18 0x00000000004822fe in hie4 (Expr=0x7ffdeb29ff80) at cc65/expr.c:2912
#19 0x00000000004810f9 in ExprWithCheck (Func=0x6ae690 <__afl_area_initial>, Expr=0x7ffdeb29ff80) at cc65/expr.c:110
#20 hie_internal (Ops=0x49f200 <hie3.hie3_ops>, Expr=0x7ffdeb29ff80, hienext=0x6ae690 <__afl_area_initial>, UsedGen=0x7ffdeb19f924) at cc65/expr.c:1877
#21 0x00000000004822be in hie3 (Expr=0x7ffdeb29ff80) at cc65/expr.c:2926
#22 0x00000000004810f9 in ExprWithCheck (Func=0x6ae690 <__afl_area_initial>, Expr=0x7ffdeb29ff80) at cc65/expr.c:110
#23 hie_internal (Ops=0x49f1e0 <hie2.hie2_ops>, Expr=0x7ffdeb29ff80, hienext=0x6ae690 <__afl_area_initial>, UsedGen=0x7ffdeb19fa64) at cc65/expr.c:1877
#24 0x0000000000483a26 in hie2 (Expr=0x7ffdeb29ff80) at cc65/expr.c:2940
#25 ExprWithCheck (Expr=0x7ffdeb29ff80, Func=<optimized out>) at cc65/expr.c:110
#26 hieAnd (Expr=0x7ffdeb29ff80, TrueLab=2774, BoolOp=0x7ffdeb19fb58) at cc65/expr.c:2997
#27 0x000000000047e932 in hieOr (Expr=0x7ffdeb29ff80) at cc65/expr.c:3063
#28 ExprWithCheck (Func=<optimized out>, Expr=<optimized out>) at cc65/expr.c:110
#29 hieQuest (Expr=<optimized out>) at cc65/expr.c:3140
#30 hie1 (Expr=0x7ffdeb29ff80) at cc65/expr.c:3514
#31 0x00000000004783ae in hie0 (Expr=0x7ffdeb29ff80) at cc65/expr.c:3571
#32 Primary (E=0x7ffdeb29ff80) at cc65/expr.c:673
#33 hie11 (Expr=<optimized out>) at cc65/expr.c:1288
#34 hie10 (Expr=0x7ffdeb29ff80) at cc65/expr.c:1845
#35 0x00000000004810f9 in ExprWithCheck (Func=0x6ae690 <__afl_area_initial>, Expr=0x7ffdeb29ff80) at cc65/expr.c:110
#36 hie_internal (Ops=0x49f1a0 <hie9.hie9_ops>, Expr=0x7ffdeb29ff80, hienext=0x6ae690 <__afl_area_initial>, UsedGen=0x7ffdeb19ffe0) at cc65/expr.c:1877
#37 0x000000000047bef6 in hie9 (Expr=0x7ffdeb29ff80) at cc65/expr.c:2438
#38 ExprWithCheck (Expr=0x7ffdeb29ff80, Func=<optimized out>) at cc65/expr.c:110
#39 hie8 (Expr=0x7ffdeb29ff80) at cc65/expr.c:2863
#40 0x00000000004771a4 in ExprWithCheck (Func=0x5d28, Expr=0x28) at cc65/expr.c:110
#41 0x000000000046b823 in ShiftExpr (Expr=0x7ffdeb29ff80) at cc65/shiftexpr.c:77
#42 0x000000000048239d in ExprWithCheck (Func=0x46b7e0 <ShiftExpr>, Expr=0x7ffdeb29ff80) at cc65/expr.c:110
#43 hie_compare (Ops=0x49f270 <hie6.hie6_ops>, Expr=0x7ffdeb29ff80, hienext=0x46b7e0 <ShiftExpr>) at cc65/expr.c:2097
```

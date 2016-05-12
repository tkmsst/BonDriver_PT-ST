オリジナルのBonDriver_PT(人柱版３)との使用する上での相違点

・BonDriverのバイナリファイルはS用もT用も同一です。
  名前が「BonDriver_PT-T.dll」あるいは「BonDriver_PT-Tx.dll」の場合はT用として、
  「BonDriver_PT-S.dll」あるいは「BonDriver_PT-Sx.dll」の場合はS用として動作するので、
  dllファイルをコピーし、名前を変更して使用して下さい。

・iniファイルの中に「PTver」の項目が増えています。
  このBonDriverをPT2で使用する人は「2」を、PT1で使用する人は「1」を指定してください。
  この値は実質ほぼ利用されていないので、EDCBで使用する場合以外は多分変更する必要はありません。
  (EDCBでは設定ファイルの名称にBonDriverのファイル名だけでなくこの値も使用している為、
   ここが間違っていると既存の設定ファイル(XXXX.ChSet4.txt)が読み込めなくなります。)

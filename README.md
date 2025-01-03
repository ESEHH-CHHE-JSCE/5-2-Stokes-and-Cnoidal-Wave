# 5-2-Stokes-and-Cnoidal-Wave
Fortran
【例題5.2】のReadme
実行ファイル「cal_faw.exe」は，FORTRAN言語で記述されたソースプログラム「cal_faw.f」をコンパイルしたものです．また，このプログラムは，Isobe et al. (1982)によって誘導された5次ストークス波理論および3次クノイド波理論に基づき，東京大学（現：高知工科大学）の磯部雅彦氏が作成し，中国・北京精華大学（現：中国・南方科技大学）の余　錫平氏が修正した，水理公式集例題プログラム集平成13年版の【例題5-基礎2】に掲載されたものを，一部改変および追記したものです．
実行ファイル「cal_faw.exe」を実行し，画面の指示に従い，波の条件（水深h，周期T，波高H）を入力してストークス波またはクノイド波を選択し，0～1の任意の位相を入力することで，選択した有限振幅波の波長と波速が「input.dat」に，1周期分の位相θと波形ηが「profile.dat」に，指定した位相における水平流速成分u，鉛直流速成分wおよび動水圧pの水深方向鉛直分布が「field.dat」にそれぞれ出力されます．
Excelブック「profile.xlsx」および「field.xlsx」には，それぞれの出力結果を描いたグラフが，同じ波の条件での微小振幅波とともに示されています．これらは，Microsoft Excel 2007以降で動作します．
これらのExcelブック（「profile.xlsx」および「field.xlsx」）において，シート名"input"のC列：3～5行目に波の条件（水深h，周期T，波高H）を入力すると，C列：8～9行目に微小振幅波の波長L，波速Cが表示されます．また，C列：12～13行目およびC列：16～17行目には，ストークス波またはクノイド波を選択して「input.dat」に出力された有限振幅波の波長と波速を入力しておくと良いですが，これらの値はグラフの描画には無関係です．
さらに，Excelブック「profile.xlsx」では，シート名"input"のQ～R列およびS～T列：3～103行目に，ストークス波またはクノイド波を選択して「profile.dat」に出力された1周期分の位相θと波形ηをそれぞれ入力します．これらの値は微小振幅波の波形が描かれたグラフに反映され，重ねて描画されます．
一方，Excelブック「field.xlsx」では，「cal_faw.exe」の実行時に画面上で指定した位相をシート名"input"のC1セルに入力し，P～S列およびT～W列：3～103行目に，ストークス波またはクノイド波を選択して「field.dat」に出力された相対水深z/h，水平流速成分u，鉛直流速成分wおよび動水圧pを入力すると，長波の波速(gh)^0.5で無次元化した水平方向および鉛直方向の水粒子速度u，v：u/(gh)^0.5，v/(gh)^0.5，および圧力ρgHで無次元化した動水圧p：p/ρgHの鉛直分布が，微小振幅波のそれらのグラフに対してそれぞれ重ねて描画されます．

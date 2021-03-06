# 図式解法の手続きについて
まず、出力特性上に直流負荷線を引く。回路図から得られる$300I_C+V_{CE}=5$の関係式により、$(V_{CE},I_C)=(0, 0.025),(5, 0)$に点を打って線を引けばいい。  
つぎに、動作点を打つ。今回は$V_{CE}$がわかっているので直流負荷線上で$V_{CE}=2.0$のところに点を打てばいい。  
そして、交流負荷線を引く。直流負荷線の式を微分して回路定数を交流のものに置き換えると$200\Delta I_C+\Delta V_{CE}=0$の関係式が得られる。よって動作点にを基準として$(\Delta V_{CE},\Delta I_C)=(1, -0.005)$に点を打って線を引けばいい。  
その後、$V_{CE}$の範囲が与えられているため交流負荷線上に動作範囲を示す。  
そうすると、$I_C$の範囲がわかるため電流伝達特性上に動作範囲を示す。  
同様にして$I_B$の範囲がわかるため入力特性上に動作範囲を示す。  
そこからわかる$V_{BE}$の範囲$\Delta V_{CE}$と$V_{CE}$の範囲$\Delta V_{CE}$から電圧増幅率を$A_V=\frac{\Delta V_{CE}}{\Delta V_{BE}}$で求めることができる。  

# 入力特性上での動作点を変えると電圧増幅率にどのような影響が出るのか
入力特性のグラフから、動作点を０側に近づけると歪んだ部分に入り電圧増幅率は小さくなる。
また、動作点を正の方向にもっていくと発散している部分に入るため電圧増幅率は大きくなる。

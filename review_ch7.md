# CH7 复习

## 7.1 金半接触和能带图
名词概念：<br>
功函数：起始能量等于费米能级的电子有金属内部溢出到真空所需的最小能量。<br>
电子亲和能：$E_0到E_c的能量间隔$<br>
接触电势差：
肖特基势垒<br>
阻挡层、反阻挡层<br>

### 能带弯曲的机理
当$W_m > W_s$时，半导体的费米能级高于金属，电子从半导体移动到金属表面，正电荷则积聚在半导体表面，由于自由电荷密度限制，半导体正电荷层表面浓度低于内部，电场从内指向外，表面的电势更低，相应电子的能量更高，能带向上弯曲，会形成势垒。
势垒区中电子浓度低，是一个高阻区，称为阻挡层。<br>
如果$W_m < W_s$的n型半导体，将会反过来，形成反阻挡层。<br>
阻挡层是电离杂质形成的厚空间电荷区，反阻挡层是多子积累的薄电荷区。<br>


### 表面态的影响：<br>
表面态对应表面能级，位于禁带中。<br>
表面能级在禁带中呈一定分布。<br>
存在一个距离价带顶$q\phi$的能级，其下的表面态空着时表面带正电，呈现施主型；其上的表面态被电子填充时表面带负电，呈现受主型。<br>
$q \phi$ 比 $E_F$ 低，会有电子先填充表面能级，直到这个表面能级与$E_F$重合，此时表面处能带会被拉高，因此能带会弯曲。<br>
势垒高度被称为**高表面态密度钉扎**。存在表面态时，即使不与金属接触也会形成势垒，当表面态密度很高时，可以屏蔽金属接触的影响，势垒高度几乎和金属的功函数无关。<br>


## 7.2 整流理论

### 扩散理论：
适用于厚阻挡层 $J = J_{sD} [exp(\frac{q V}{k_0 T}) - 1]$ <br>
当V很大时，$q V >> k_0 T$ 有$J = J_{sD} exp(\frac{q V}{k_0 T})$

### 热电子发射理论：
$J = J_{sT} [exp(\frac{q V}{k_0 T}) - 1]$ <br>
其中$J_{sT} = A^* T^2 exp(-\frac{q \phi_{ns}}{k_0 T})$，$A = 120 A/(cm^2*K^2)$， $\frac{A^*}{A}$的值可以查表得到。 <br>
$J_{sT}$与电压无关


### 镜像力和隧道效应
镜像力会是势垒降低；隧道效应也会使势垒降低，并且反向电压越高，势垒降低越多。<br>
因此会导致：
1. 反向电流增大
2. 反向击穿电压降低，更容易发生击穿
3. 漏电流更多，功耗更大

### 肖特基二极管
肖特基二极管是多子器件，载流子穿过界面进入金属不会发生积累，因此具有更好的高频特性。<br>
反向饱和电流更大，正向导通电压更低<br>
广泛应用与高速集成电路，微波技术。<br>



## 7.3 欧姆接触
欧姆接触不产生明显附加阻抗。
形成方式：
1. $W_m < W_s$的金属n型半导体接触 <br>
2. $W_m > W_s$的金属p型半导体接触 <br>

但实际上半导体表面态密度都很高，因此不能用这种方法；而是利用隧道效应，重掺杂可以产生接近理想的欧姆接触。通常的做法是在n型或p型半导体上制作一层重掺杂区后再与金属接触。<br>





















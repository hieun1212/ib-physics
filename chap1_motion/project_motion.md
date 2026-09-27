## Chuyển động ném

### Chuyển động ném ngang

Xét một vật được ném ngang từ điểm O ở độ cao H so với mặt đất. Chọn hệ quy chiếu như hình vẽ.

![Chuyển động ném ngang](images/project_motion1.png){width="70%" fig-align="center"}

Xét theo phương Ox: vật chuyển động thẳng đều nên ta có:

$$
\begin{dcases}
  v_x = v_{0} \\ 
  x = v_x t = v_{0}t \tag{1}
\end{dcases}
$$

Xét theo phương Oy: vật rơi tự do với vận tốc ban đầu bằng 0 nên ta có:

$$
  \begin{dcases}
  v_y = gt \\ 
  y = \frac{1}{2} gt^2 \tag{2}
  \end{dcases}
$$

Từ (1) ta rút ra được $\displaystyle t = \frac{x}{v_{0}}$, thay vào (2):
$$
  y = \frac{1}{2} g \left( \frac{x}{v_{0}} \right)^2 = \frac{g}{2v_{0}^2} x^2
$$
Quỹ đạo chuyển động là một nhánh parabol.

- Thời gian rơi: $\displaystyle H = y = \frac{1}{2}gt^2 \implies t = \sqrt{\frac{2H}{g}}$
- Tầm bay xa của vật theo phương ngang: $\displaystyle L = x_{\max} = v_{0}t = v_{0} \sqrt{\frac{2H}{g}}$
- Vận tốc của vật tại một thời điểm bất kỳ: $v = \sqrt{v_x ^2 + v_y ^2}$
- Phương của vận tốc hợp với phương ngang một góc $\alpha$:
$$
  \tan \alpha = \frac{v_y}{v_x}
$$


::: {.callout}

**Ví dụ 1.** Một mũi tên được phóng đi theo phương ngang từ đỉnh một toà tháp cao 35 m. Vận tốc ban đầu là 30 m/s. Giả sử lực cản không khí là không đang kể. Tính:\
a. Thời gian mũi tên bay đến khi chạm đất.\
b. Khoảng cách từ chân tháp đến nơi mũi tên chạm đất.\
c. Vận tốc của mũi tên khi chạm đất.

::: {.text-center}
**Giải**
:::

Chọn hệ quy chiếu với gốc toạ độ tại đỉnh tháp, trục $Ox$ hướng từ trái sang phải, trục $Oy$ hướng xuống dưới. Ta có:
$$
  \begin{aligned}
    v_x &= v_{0x} = v_0 = 30 \\ 
    v_y &= v_{0y} + at = 9.8 t
  \end{aligned}
$$

Phương trình chuyển động theo các phương Ox, Oy là:
$$
  \begin{aligned}
    x &= x_{0} + v_{0x}t = 30 t \\ 
    y &= y_{0} + v_{0y}t + \frac{at^2}{2} = 4.5 t^2
  \end{aligned}
$$
a\. Mũi tên chạm đất khi $y = 35$ m:
$$ 4.5 t^2 = 35 \quad \text{hay} \quad  t = 2.67 \text{s} $$ 

b\. Khoảng cách từ chân cột đến điểm rơi:
$$ x = 30 t = 30 \times 2.67 = 80.1 ~\text{m} $$

c\. Để tính vận tốc của mũi tên, ta tính vận tốc theo phương Ox và Oy. Ta có $v_x = 30$ m/s, $v_y = 9.8 t = 9.8 \times 2.67 = 26.2$ m/s.

Vận tốc của mũi tên là: $v = \sqrt{v_x ^2 + v_y ^2} = \sqrt{30^2 + 26.2^2} = 39.8$ m/s. Góc của vận tốc so với phương ngang là
$$
  \tan \alpha = \frac{v_y}{v_x} = \frac{26.2}{30} \Rightarrow \alpha = 41^\circ
$$

**Ví dụ 2.** Một vật được ném theo phương ngang từ một con tàu và rơi xuống biển sau 1.6 s ở vị trí cách con tàu 37 m. Tính:\
a\. Vận tốc ban đầu của vật.\
b\. Độ cao ban đầu của vật so với mực nước biển.

::: {.text-center}
**Giải**
:::
Chọn gốc toạ độ tại vị trí ném vật, trục Ox hướng sang phải, trục Oy hướng xuống dưới.\
a. Vật di chuyển 37 m theo chiều ngang trong 1.6 s, vận tốc theo phương ngang là $v = v_x = \frac{37}{1.6} = 23$ m/s.\
b. Phương trình chuyển động của vật theo phương Oy là: $y = y_{0} + v_{0y}t + \frac{at^2}{2} = 4.5 t^2$.

Vật chuyển động trong 1.6 s, nên chiều cao là $y = 4.5 \times 1.6^2 = 12.5$ m.

:::


### Chuyển động ném xiên

Xét một vật được ném xiên từ điểm O trên mặt đất với vận tốc ban đầu $\vec{v}_0$ hợp với phương ngang một góc $\theta$.

![Chuyển động ném xiên](images/project_motion2.png)

Theo $Ox$ vật chuyển động thẳng đều. Theo phương $Oy$ vật chuyển động có gia tốc $-g$. Do đó:
$$
  \begin{align}
    v_x &= v_{0x} = v_{0}\cos \theta \\
    v_y &= v_{0y} - gt = v_{0}\sin \theta - gt
  \end{align}
$$

Phương trình chuyển động của vật trên hai phương $Ox$ và $Oy$ là:
$$
  \begin{align}
    x &= v_x t = v_{0} t \cos \theta \tag{1} \\
    y &= v_{0y}t - \frac{1}{2}gt^2 = v_{0}t \sin \theta - \frac{1}{2}gt^2 \tag{2}
  \end{align}
$$


Từ (1) ta được
$$
  t = \frac{x}{v_{0} \cos \theta }
$$
thay vào (2):
$$y = v_0 \sin \theta  \cdot \frac{x}{v_0 \cos \theta} - \frac{1}{2}g \left(\frac{x}{v_0 \cos \theta }\right)^2 = -\frac{g}{2v_0^2 \cos^2 \theta} x^2 + x \tan \theta $$

Vậy quỹ đạo chuyển động là một đường parabol.

Vận tốc trên phương $Oy$ thoả:
$$
  v_y ^2 - v_{0y}^2 = -2gy
$$
Mà $v^2 = v_y ^2 + v_x ^2$ và $v_0 ^2 = v_{0y}^2 + v_{0x}^2$. Hơn nữa, $v_{0x}^2 = v_x ^2$ nên
$$
  v^2 - v_{0}^2 = -2gy \tag{*}
$$

Vật đạt độ cao cực đại khi $v_y = 0$:
$$
  \begin{align}
    & 0 = v_{0}\sin \theta - gt \\ 
    &\Rightarrow t = \frac{v_{0}\sin \theta}{g}
  \end{align}
$$

Vật rơi trở lại mặt đất khi $y = 0$
$$
  0 = v_{0}t \sin \theta - \frac{1}{2}gt^2
$$
giải phương trên ta được
$$
  t = \frac{2v_{0} \sin \theta}{g}
$$
thời gian chuyển động gấp đôi thời gian vật đạt được độ cao cực đại.

Thay vào phương trình $x$, ta được tầm xa của vật
$$
  x_{\max} = v_{0} \frac{2v_{0}\sin \theta}{g} \cos \theta =  \frac{v_{0}^2 \sin 2\theta }{g}.
$$


::: {.callout}
**Ví dụ 1.** Một vật được phóng đi với vận tốc $18$ m/s theo một góc:
a\. $30^\circ$ so với phương ngang.
b\. $0^\circ$ so với phương ngang.
c\. $90^\circ$ so với phương ngang.
Tìm thành phần theo phương $Ox$ và $Oy$ của vận tốc đầu trong mỗi trường hợp

**Ví dụ 2.** Một vật được phóng theo một góc $32^\circ$ so với phương ngang với vận tốc ban đầu $25$ m/s.Xác định độ cao mà vật đạt được và tầm xa của vật. Lấy $g = 9.81$ m/s^2^.

::: {.text-center}
**Giải**
:::
Thành phần theo phương $Ox, Oy$ của vận tốc ban đầu là:
$$
  v_{0x} = v_{0}\cos \theta, \qquad v_{0y} = v_{0}\sin \theta.
$$

Vật đạt độ cao cực đại khi $v_y = v_{0} \sin \theta - gt$ bằng $0$,
$$
  25\sin 32^\circ - 9.81 \cdot t = 0 \Rightarrow t = 1.35 ~\text{s}
$$
Phương trình chuyển động theo phương $Oy$ là:
$$
  y = v_{0y}t - \frac{gt^2}{2} = v_{0}t\sin \theta - \frac{gt^2}{2}  
$$
Thay $t = 1.35$ s, ta được:
$$
  y_{\max} = 25\cdot 1.35 \cdot \sin 32^\circ - \frac{9.81 \cdot 1.35^2}{2} = 8.95 ~\text{m}
$$

Vật rơi trở lại mặt đất khi $y = 0$, giải phương trình ta được $t = 2.70$ s. Thay vào phương trình chuyển động theo phương $Ox$:
$$
  x = v_{0x}t = v_{0}t\cos \theta
$$
ta được $x_{\max} = 25 \cdot 2.7 \cdot \cos 32^\circ = 57.24$ m.

:::

### Bài tập tự luyện {.unnumbered}

**Bài 1.** Từ độ cao H = 10 m, người ta ném một vật lên cao theo phương thẳng đứng với vận tốc $v_{0} = 20$ m/s. Lấy $g = 10$ m/s^2^. Tính:\
a. Thời gian để vật lên đến độ cao cực đại và độ cao cực đại đó.\
b. Vận tốc của vật khi rơi đến mặt đất và thời gian từ lúc ném vật đến lúc rơi đến đất. 

**Bài 2.** Hai vật được ném thẳng đứng lên cao từ cùng một điểm với $v_{0} = 25$ m/s, vật II sau vật I khoảng thời gian $t_{0} = 0.5$ s. Lấy $g = 10$ m/s^2^.\
a. Hỏi hai vật gặp nhau sau khi ném vật II bao lâu và ở độ cao nào?\
b. Tìm điều kiện của $t_{0}$ để hai vật có thể gặp nhau?

**Bài 3.** Một vật được ném theo phương ngang, sau thời gian $0.5$ s vật rơi cách vị trí ném 5 m. Tìm:\
a. Độ cao của nơi ném vật.\
b. Vật tốc lúc ném vật.\
c. Vận tốc khi vật chạm đất.\
d. Góc hợp bởi phương vận tốc và phương ngang sau khi ném 0.2 s. Lấy $g = 10$ m/s^2^.

<!-- Bài tập từ IB-physic -->

**Bài 4**. Một quả bóng lăn khỏi bàn theo phương ngang với tốc độ 2 m/s. Bàn cao 1.3 m. Tính khoảng cách từ chân bàn đến vị trí bóng rơi trên mặt đất.

**Bài 5**. Hai vật nằm trên cùng một đường thẳng đứng, từ độ cao lần lượt là 4 m và 8 m, được ném theo phương ngang với vật tốc 4 m/s.\
a. Tính khoảng cách vị trí rơi của hai vật trên mặt đất.\
b. Để vật ở độ cao 4 m rơi cùng vị trí với vật ở độ cao 8 m thì vật tốc ném ban đầu của nó phải là bao nhiêu.

**Bài 6**. Một vật được ném theo hướng $40^\circ$ so với phương ngang với vận tốc ban đầu 20 m/s. Viết phương trình:\
a. Vận tốc ngang theo thời gian.\
b. Vận tốc dọc theo thời gian.\
c. Vận tốc theo thời gian.

**Bài 7**. Xác định độ cao cực đại mà một vật được ném theo hướng $40^\circ$ với vận tốc 24 m/s đạt được.

**Bài 8**. Một vật được ném với vận tốc 20 m/s theo một góc $50^\circ$ so với phương ngang. Viết phương trình:\
a. Chuyển động của vật theo phương $Ox$.\
b. Chuyển động của vật theo phương $Oy$.

**Bài 9**. Một hòn đá được ném từ một vách đá cao 60 m so với mặt biển. Vận tốc ném ban đầu là 20 m/s hợp với phương ngang một góc $48^\circ$.\
a. Tính vận tốc (độ lớn và hướng) của hòn đá khi chạm mặt biển.\
b. Lực cản không khí sẽ tác động như thế nào đến kết quả ở câu a.

**Bài 10.** Một hòn đá được ném từ độ cao $2.1$ m so với mặt đất với góc ném $\alpha = 45^\circ$ so với phương ngang. Hòn đá rơi đến cách chỗ ném theo phương ngang một khoảng 42 m. Tìm:\
a. Vật tốc của hòn đá khi ném.\
b. Thời gian hòn đá rơi.\
c. Độ cao lớn nhất mà hòn đá đạt đến. Lấy $g = 9.8$ m/s^2^.

<!-- Bài tập từ sách ôn luyện vật lý -->

**Bài 11**. Một vận động viên nhảy từ một bờ sông này qua bên kia sông như hình vẽ. Hỏi vận động viên phải nhảy với vận tốc ban đầu tối thiểu bằng bao nhiêu để có thể qua được bờ bên kia. Lấy $g = 10$ m/s^2^, bỏ qua lực cản không khí.

![](/images/exercise20_p22.png){fig-align="center" width=70%}

**Bài 12**. Một người lính cứu hoả đứng cách toà nhà một khoảng $d = 10$m, hướng dòng nước từ vòi chữa cháy theo một góc $\theta$ so với phương ngang như hình vẽ. Biết vận tốc dòng nước khi ra khỏi vòi là 15 m/s và coi như vòi nước gần sát mặt đất. Tìm góc $\theta$ để dòng nước có thể rơi vào trúng một đám cháy ở độ cao $h = 8.6$m.

![](/images/exercise21_p22.png){fig-align="center" width=70%}

**Bài 13**. Một vận động viên trượt tuyết rời khỏi máng trượt với vận tốc v = 10m/s hướng lên hợp với phương ngang một góc θ = 15°. Nơi cô ấy tiếp đất là một sườn dốc nghiêng một góc φ = 50°, bỏ qua lực cản của không khí.\
a. Tìm khoảng cách từ vị trí vận động viên rời máng trượt đến vị trí vận động viên tiếp đất.\
b. Tính vận tốc của vận động viên ngay khi tiếp đất.

**Bài 14**. Một sân chơi nằm trên sân thượng của một trường học có độ cao 6m so với mặt đường. Bức tường thẳng đứng của tòa nhà cao h = 7m so với mặt đường tạo thành một lan can cao 1m bao quanh sân chơi. Một nhóm học sinh đang chơi bóng trên sân thượng vô tình làm rơi quả bóng xuống đường. Một người qua đường đá quả bóng bay lên sân thượng theo một góc nghiêng θ = 53° so với phương ngang và ở điểm cách chân tường một khoảng d = 24m. Quả bóng mất 2,2s để đến một điểm trên cao thẳng đứng phía trên bức tường.\
a. Tìm tốc độ mà quả bóng được đá đi từ mặt đất.\
b. Tìm độ cao của quả bóng so với đỉnh bức tường khi nó bay ngang qua bức tường.\
c. Tìm khoảng cách theo phương ngang từ bức tường đến điểm rơi của quả bóng trên sân thượng.

![](/images/exercise23_p23.jpg){fig-align="center" width=70%}

**Bài 15**. Một vận động viên quần vợt đang giao một quả bóng theo phương ngang. Quả bóng được đánh đi ở độ cao 2,5m và cách lưới theo phương ngang một đoạn 15m, lưới có chiều cao 0,9m.\
a. Hỏi tốc độ ban đầu tối thiểu của bóng là bao nhiêu để nó qua được lưới?\
b. Quả bóng sẽ chạm đất ở đâu nếu nó vừa lọt qua được lưới (sẽ là tốt nhất nếu quả bóng rơi cách lưới trong vòng 7m)

![](/images/exercise24_p23.jpg){fig-align="center" width=70%}


<!-- Bài tập từ sách bồi dưỡng hình học bài 7 -->

<!-- **Bài 1-7/** Một vật rơi tự do từ độ cao h. Cùng lúc đó một vật khác được ném thẳng đứng xuống từ độ cao H ( H > h) với vận tốc ban đầu v₀. Hai vật tới đất cùng một lúc. Tìm v₀.

**Bài 2-7/** Người ta ném đồng thời hai vật lên cao theo phương thẳng đứng. Vật I từ mặt đất với v₀₁ = 20 m/s và vật II từ độ cao H = 5 m với v₀₂ = 10 m/s. Hai vật gặp nhau sau thời gian bao lâu? Lấy g = 10 m/s².

**Bài 3-7/** Một quả bóng được ném theo phương ngang với tốc độ v₀ = 25 m/s và rơi xuống đất sau 3 s. Lấy g = 10 m/s².\
a. Bóng ném từ độ cao nào?\
b. Bóng đi xa một đoạn bằng bao nhiêu?\
c. Tốc độ bóng khi chạm đất.

**Bài 4-7/** Một quả cầu được ném theo phương ngang từ độ cao 80 m. Sau khi chuyển động được 3s vận tốc quả cầu hợp với phương ngang góc 45°.\
a. Tìm vận tốc ban đầu của quả cầu.\
b. Quả cầu sẽ chạm đất lúc nào? Ở đâu? Với vận tốc bao nhiêu? Lấy g = 10 m/s².

**Bài 5-7/** Một thang máy chuyển động lên cao với gia tốc 2 m/s². Lúc thang máy có vận tốc 2,4 m/s thì từ trần thang máy có một vật rơi xuống. Trần thang máy cách sàn đoạn h = 2,47 m. Lấy g = 10 m/s². Hãy tính trong hệ qui chiếu gắn với mặt đất:\
a. Thời gian vật rơi.\
b. Độ dịch chuyển vật.\
c. Quãng đường vật đã đi được.

**Bài 6-7/** Một người làm xiếc tung các quả bóng lên cao. Quả nọ sau quả kia, quả sau rời tay người làm xiếc khi quả trước đạt độ cao cực đại. Cho biết mỗi giây có hai quả bóng được tung lên. Hỏi các quả bóng được ném lên cao bao nhiêu. Lấy g = 9,8 m/s².

**Bài 7-7/** Một tên lửa được phóng theo phương thẳng đứng và chuyển động với gia tốc 2g trong thời gian động cơ hoạt động là 50 s. Lấy g = 10 m/s².\
a. Tìm độ cao cực đại mà tên lửa đạt đến.\
b. Tính thời gian từ lúc phóng đến lúc tên lửa trở lại mặt đất. Bỏ qua sức cản không khí và sự thay đổi của gia tốc theo độ cao.

**Bài 8-7/** Một vật được ném lên thẳng đứng với vận tốc 4,9 m/s. Cùng lúc đó tại điểm có độ cao bằng độ cao cực đại mà vật lên tới, người ta ném xuống thẳng đứng một vật khác cùng với vận tốc 4,9 m/s. Sau bao lâu hai vật đụng nhau? Lấy g = 9,8 m/s².

**Bài 9-7/** Một vật rơi tự do từ A ở độ cao (H + h). Vật thứ hai được phóng lên thẳng đứng với vận tốc v₀ từ mặt đất tại C.\
a. Hai vật bắt đầu chuyển động cùng lúc. Tìm v₀ để hai vật gặp nhau ở B có độ cao h. Độ cao tối đa mà vật thứ hai lên tới là bao nhiêu? Xét trường hợp riêng khi H = h.\
b. Vật thứ hai được phóng lên trước hoặc sau vật thứ nhất một khoảng thời gian t₀. Biết hai vật gặp nhau tại B và độ cao cực đại của vật thứ hai là h. Tìm t₀ và v₀.

**Bài 10-7/** Tại một địa điểm hai vật được ném lên theo phương thẳng đứng với cùng một vận tốc ban đầu v₀. Nhưng cách nhau khoảng thời gian t₀.\
a. Tìm vận tốc tương đối của vật II so với vật I\
b. Khoảng cách hai vật thay đổi theo qui luật nào?
Áp dụng: v₀ = 2 m/s; t₀ = 2s

**Bài 11-7/** Một quả bóng được buông rơi từ A ở độ cao h₀ xuống sàn ngang nhẵn. Khi bóng chạm sàn nó nảy lên với vận tốc bằng vận tốc lúc chạm nhưng ngược chiều. Khi quả bóng (I) chạm sàn thì quả bóng (II) được thả ra cũng từ A.\
a. Hỏi sau bao lâu kể từ lúc thả quả bóng II và ở độ cao nào hai quả bóng gặp nhau.\
b. Nếu gặp nhau hai quả bóng va chạm tuyệt đối đàn hồi, thì sau đó chúng chuyển động ra sao? Biết hai quả bóng giống nhau và va chạm tuyệt đối đàn hồi thì chúng trao đổi vận tốc cho nhau. Tìm thời gian hai bóng rơi đến sàn kể từ lúc chạm nhau.

**Bài 12-7/** Một máy bay bay ngang với vận tốc v₁ ở độ cao h muốn thả bom trúng một tàu chiến đang chuyển động đều với vận tốc v₂ trong cùng một mặt phẳng thẳng đứng với máy bay. Hỏi máy bay phải cắt bom khi nó cách tàu chiến theo phương ngang một đoạn ℓ là bao nhiêu? Xét hai trường hợp:\
a. Máy bay và tàu chuyển động cùng chiều.\
b. Máy bay và tàu chuyển động ngược chiều.  

**Bài 13-7/** Người ta đặt một súng cối dưới một căn hầm có độ sâu h. Hỏi phải đặt súng cách vách hầm một khoảng ℓ bao nhiêu so với phương ngang để tầm xa x của đạn trên mặt đất là lớn nhất? Tìm tầm xa này. Biết vận tốc đầu của đạn khi rời súng là v₀.

**Bài 14-7/** Từ A cách đất khoảng AH = 45 m, người ta ném một vật với vận tốc v₀₁ = 30 m/s theo phương ngang. Lấy g = 10 m/s².\
a. Trong hệ quy chiếu nào vật chuyển động với gia tốc g? Trong hệ quy chiếu nào vật chuyển động thẳng đều? Viết phương trình chuyển động của vật trong mỗi hệ quy chiếu.\
b. Cùng lúc ném vật từ A, tại B trên mặt đất với (BH = AH) người ta ném lên một vật khác với vận tốc v₀₂. Xác định v₀₂ để hai vật gặp được nhau. -->

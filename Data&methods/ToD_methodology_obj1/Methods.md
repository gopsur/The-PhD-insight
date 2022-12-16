
$$\color{olive}{\ Reference\\ period}$$



      > removed 1890-1950 monthly climatology (our reference period; we test departures from that period)
      > Secondary ref period: For ref period check, 1920-1970 Here all the analysis styarts from 1920 onwards
      


$${\color{red}Global \\ warming \\ index \\ W(t)}$$


      > 4th order (as in H&S) polynomial fit over the 1890-2100 period* to the tropical average of  SST anomalies 30°S to 30°N
      > zero- padding at the beginning of time series for 60 years (i.e. during 1831-1890 [1861-1920] ) to ensure near-zero trend during the reference period 1890-1950 [1920-1970]
      > the only exception is when we will compare with observations, where T<sub>end</sub> =2020

      
      
$${\color{blue}Signal \\ Estimation}$$
      > Local time series	${\color{green} 𝑌(𝑡)=𝑆 ̃(𝑡)+𝑁 ̃(𝑡)}$ <br />
      > Signal		${\color{yellow} 𝑆 ̃(𝑡)=𝑎 ̃+𝑏 ̃𝑊(𝑡)}$ <br />
   <img width="435" alt="Screenshot 2022-12-16 at 2 58 26 PM" src="https://user-images.githubusercontent.com/89978878/208067283-ad36104d-01e9-4de1-9cd1-eb8ae98054b6.png"> <br />
      > a and b estimated over [1890,T<sub>end</sub>] where end range 1950 to 2100[2020] increment 1 year each
      
      

$${\color{brown}Noise \\ Estimation}$$
      > Noise S as an unbiased estimate of the standard deviation of the residual term N  <br />
      > 𝑌(𝑡)−𝑆(𝑡) and s=Std(N(t)) is the noise over 1890-2100  <br />
      <img width="357" alt="Screenshot 2022-12-16 at 3 38 27 PM" src="https://user-images.githubusercontent.com/89978878/208075017-10ce949a-26fc-4e0a-9585-6e839ae2ebbf.png">  <br />
    

$${\color{brown}H&S \\ Method}$$
      > |S(t)|>threshold *s
      >

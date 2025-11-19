原有(S0,S1)兩個狀態讓count1和count2計數，為儲存state上一次的狀態，增加狀態S2及增加state1變數。
說明： 從S0開始，此時count1會開始數到9，count2會維持為253。 當count1計數到8時：下個clk將state變成S2，state1會變成S1且count1變成9。
state為S2：依state1為S0或S1決定state下個狀態為S1或S0。 state1 = S0 => state = S1 , state1 = S1 => state = S0
count2也是，從253計數到79。

# Trade / stay vested notes

## 5 layer filters 
   
   1. Market Cap > 7000 cr
      Eliminate the Penny
   2. Sales Growth (10 yrs) > 10% for consequitive years 
      not profit
       Catch the quality product/service being offered
   3. 10 yr AVG ROCE > 15%
   4. Promoter Holding > 33% 
      earliest to know news and start reflecting in patterns
   5. SharePrice growth > 17 %
      Share Price ( current Market Price growth trend in last 10 years
   
   
   SCREENER :
   ```
   Market Capitalization > 7000 AND Sales growth 10Years > 10% AND Average return on capital employed 10Years > 15% AND Promoter holding >33% AND Return over 10years >17%
   ```

## 1 Screen Companies  
 1. Screener queries ( already available )  
      i) Short term swing buckets  
     ii) Long term buckets  
    iii) ** Day trade volatility buckets - ATR  / ADX plot > 25 ?   
 2. Screener Credit Rating  
 3. Screen queries ( already available )  
 4. Create Buckets with Market Caps etc.  
 
## Technical charts and hunt for ( Define Tech Charts which cover the following ):  
1. SUPPORT and RESISTANCE  
     i) What is my SUPPORT level indicator ( BUY emotion close to this )  
    ii) what is my RESISTANCE level indicator ( SELL emotion close to this )  
   iii) Pivots - last pivots to understand resistance/ support ??  
                A Level 2 up Macro pivots.  
  
2. Trend Change indicators ( ENTRY / EXIT )  
   i) NORMAL ENTRY / EXIT  
  ii) SHORT ENTRY / EXIT  
    
3. Trend persistance Indicator  ( WAIT to ENTER / WAIT to EXIT )  
  i) What is my indicator to tell me to hold on to a position.ADX + Ichimoku at varying period.  
     ADX Micro breakout at 27+ ? && Ichimoku Macro stay per Resistance/support.  
    
4. SHORT / Margin charges and identify operation cost.  


  
### 1.MACD   
  i) Trend Indicator and the cross overs to be considered with other entry/exits logic and crossovers  
     * MACD Line (x)        :    (12day EMA) - (26day EMA )  
     * Signal Line (y)      :      9 day EMA of MACD Line   
     * MACD Histogram (x-y) :  (MACD Blueline) - (Signal Line)  
        
 ii) Momentum indicator using the MACD histogram  
 
  #### Takeaways  
    > MACD ( leading ) is increasing on the +0 region = Stronger rise  
    > MACD ( leading ) is increasing on the -0 region = Slugish rise  
    > * same applies for the fall of price per region correspondingly.  
   
      
### 2. Stochastic Indicator / RSI's(better brother)  
  Measure the momentum of price.E.g Rocket going up in air must slow down before it turnsdown.  
  Not to always short when overbought , impose with other charts ( MACD ) to identify longer trend.  
  Entry trigger -> look for over sold making upward cuts(20%)  
  Alternate to RSI when used with MACD Histogram and volume profile.  
  
### 3.ADX & DMI(+) (-)  
 To catch Momentum + Trade Direction + Chance of change in momentum.For trade the prime hunt should be volatility nedded for the movement alongside momentum.  
        
   @Takeaways  
     i) Probable trends starts at crossover on/above 25 ( NOT BELOW)  
         Crossovers below 25 leads to sideways and loose on brokerage rather than true trends  
     i) Crossover should make a higher pivot above the previous pivot of opposite DMI ( Very Imp)  
     iii) Trade at BREAKOUT or PullBACK ..?  
  
### 4. Candlestick: ( Always has to be tied with other charts NOT in ISOLATION )  
  Longer wick = confusion or rejection ( apply to both green and red)  
                Selling or buying pressure  
  Longer Body = conviction  
    
 * T.A.E patterns Trend / Areas of Value / Entry Trigger  
    Bullish Engulfing Pattern - bull engulfed last bear  
    Bearish Engulfing Pattern  
      
    Hammer and Shooting star : Bullish/Bearish Reversal patterns  
      
    Dragonfly Doji :  
      
    Morning and Evening Star : Bullish/Bearish Reversal patterns  
      
    Tweezer bottom and top :  Bullish/Bearish Reversal patterns  
      
 * Trend: If the price is above the 200 MA , have a long basis   
          If Price is below the 200MA , have a short basis  
 * Area of value:  
    Support/Resistance  
    Moving Average  
    Trendline  
    Channel  
      
 * Entry Trigger:  
    Reversal candlestick patterns  
      
### 5. Ichimoku - https://www.youtube.com/watch?v=68deWblNcIM  
 ( Dynamic support and Resistance level + price trend / direction / momentum ). Equillibrium at a glance , indicator for price to be able tomove strongly in one direction. Cloud is the dominant factor in general.  
   
  #### Color code and configs for 5 lines    
   CANDLE TYPE --> Volume Candle  
   
   RED    : Base Line - 26 P avg  
   BLUE   : Conversion Line - 9 P avg  
   GREEN  : Leading SpanA  - Mid point of above 2 lines      | Cloud Boundary  
   ORANGE : Leading SpanB - Mid point of 52P plot 26P future | Cloud Boundary  
   YELLOW : Lagging Span   
        
  #### Entry along with other charts ( Long or Short )        
   i) Bullish Criteria ( Entry  = for long  / EXIT per support  )  
     a) lagginSpan-26P YELLOW   ABOVE  candle   
     b) candle                  ABOVE  cloud   
     c) candle                  ABOVE  conversion-9 BLUE   
     d) conversion-9 BLUE       ABOVE  base-26 RED   
     e) cloud = green   
  
     LONG/BULL = ( Yellow > Candle > Blue > Red ) && ( cloud = Green )  
         
   ii) Bearish Criteria ( Entry = for Short / EXIT per Resistance )    
     a) lag-26P-YELLOW          BELOW  candle   
     b) candle                  BELOW  conversion-9PAvg BLUE     
     c) conversion-9 BLUE       BELOW  base-26 RED     
     d) candle                  BELOW  cloud       
     e) cloud = RED   
     
     SHORT/BEAR = ( Yellow < Candle < BLUE < RED ) && ( cloud = RED )  
       
  iii) NOISE / Trendless : Candle overlappring with Base and Conversion ines near cloud.   
    
  #### Takeaways   
    i)  Delayed Entry ! use other indicators but this to confirm.   
    ii) Form this as the second filter to indicate holding during bull/bear runs.  
    iii) ** Exit at Resistance and Support levels in order of risk taking  
          a) 1st level - BLUE  ( Conversion Line )  
          b) 2nd level - RED   ( Base line )  
          c) superimpose with my other indicator and keep Ichimoku at one period above the ADX period.  
             Intent let Ichimoku govern macro trend , while verifying micro trends with ADX & Super trend.   

 ### 6. VWAP ( Refer only IntraDay )
   The average price a security has traded at throughout the day, based on both volume and price.
   
   #### Takeaways
     i) VWAP is a single-day indicator, and is restarted at the open of each day.
     ii) More effective in initial half of the day as volume used is calulated in cumulative fashion- tough to show significant changes even for larger price changes end of day.
     iii) VWAP to be used with other indicator more towards start of day trade ( DI / Aroon )
     iv) Anti-pattern strategy could be : breakout during initial times and wait for correction to get close towards VWAP.
         Pro-pattern strategy could be : general trend defined at start of day continues.
         * ( Use other indicators as per )
   
    
    
  ## Relevant sites  
   1. stockaxis.com - validate recommendations
   2. screener - practive screens 
   3. stockedge - FII / DII movements and news.
   

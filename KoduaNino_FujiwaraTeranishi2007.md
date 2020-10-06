
# Fujiwara and Teranishi (2007)


# <strong>["A dynamic new Keynesian life-cycle model: Societal aging, demographics,and monetary policy"](https://reader.elsevier.com/reader/sd/pii/S0165188907001972?token=E3A61757391AB157E73B39D7422FEC6D36BF96EAE15426E79592E442AD8C6F40C64C934E17B9A5A8A7C7EDE111CBA1DC)

* Notebook created by Nino Kodua
* October 5, 2020

# Summary

The motivation of the paper is to explore societal aging that we see in some of the industrial economies. Societal aging implies that the central bank should have a greater interest in how monetary policy might be affecting heterogeneours agents (workers & retirees), as well as how the different demographic structures change the responces to different shocks in the economy. 

* A dynamic New Keynesian model 
* Incorporates life-cycle behavior from a la Gertler (1999)
* A dynamic stochastic general equilibrium model (DSGE)
* nominal rigidities and investment adjustment costs
* Assumption: Perfect foresight with one-time unanticipated shocks

Main research questions:
* Do structural shock impact heterogeneous agents asymmetrically? 
* Do life-cycle and different demographic structures alter dynamic responces? 


Not many research explore a monetary business cycle model with heterogeneous agent within a life-cycle model. 

# The Model

The model is based on a la Gertler (1999). Here, authors also introduce a sticky price mechanism with endogenous capital. This type of model in literature is referred as the "canonical model".

There are 6 agents in the model: firms, capital producers, financial intermediaries, households, government and the central bank. 

### Firms

* Monopolistically competitive firms
* Firms face a cost minimization problem (CMP) via price setting subject to a Rotemberg (1982) adjustment cost
* Cobb-Douglas production technology

1. Marginal Cost

Each firm j minimizes total costs:  
<ul>
    $\frac{W_t}{P_t}$$L_j,_t$ + $r_t^K$$K_j,_t$ 
    </ul>
    <ul>
            s.t. $Y_j,_t$ = [$Z_t$exp($z_t$)$L_j,_t$]<sup>$(1-\alpha)$</sup>$K_j,_t$<sup>$\alpha$</sup>
            </ul>
            where $r$<sup>K</sup> is the real cost of capital, $\alpha$ is a capital share, Z is a deterministic technology shock, and z is a temporary technology shock
    

2. Price Setting

Each firm j sets prices to maximize discounted sum of real dividends, D:
<ul>
    $D_j,_t$ = $(1+\tau)$$\frac{P_j,_t}{P_t}$$Y_j,_t$ - $\phi_t$$Y_j,_t$ - $\frac{\Phi}{2}$($\frac{P_j,_t}{P_j,_{t-1}}-1)$<sup>2</sup>$Y_t$
    </ul>
    <ul>
    s.t. $Y_j,_t$ = $(\frac{P_j,_t}{P_t})$<sup>-$\kappa$</sup>$Y_t$
    </ul>
    where $\phi$ is a real marginal cost, $\Phi$ is a cost parameter and $\tau$ ($\tau$ = $\frac{1}{\kappa -1}$) denotes a production subsidy to eliminate distortion from monopolistic competition

### Capital Producers

Maximize profits under a perfectly competitive market:
<ul> 
    $\Pi_t$<sup>K</sup> = $\frac{A_{t+1}}{P_t}$ + $r_t$<sup>K</sup> - $I_t$ - $R_t$<sup>K</sup>$\frac{A_t}{P_t}$
    </ul>
    <ul>
    s.t. $K_{t+1}$ = (1 - $\delta$)$K_t$ + [1 - S($\frac{I_t}{I_{t-1}}$)]$I_t$
    </ul>
    where S(.) is the adjustment cost function. 

### Financial Intermediaries

* lend funds to the capital producers
* hold equity of equity of the final goods producers & the capital producers

Financial intermediaries maximize their profits:
<ul> 
    $\Pi_t$<sup>FI</sup> = $R_t$<sup>K</sup>$\frac{A_t}{P_t}$ + ($\bar{P}_t$<sup>F</sup> + $D_t$)$x_t$<sup>F</sup> + ($\bar{P}_t$<sup>K</sup> +  $\Pi_t$<sup>K</sup>) $x_t$<sup>K</sup> - $\bar{P}_t$<sup>F</sup>$x_{t+1}$<sup>F</sup> - $\bar{P}_t$<sup>K</sup>$x_{t+1}$<sup>K</sup> - $\frac{A_{t+1}}{P_t}$ + $\frac{(F{A_{t+1}}^w + F{A_{t+1}}^r)}{P_t}$ - $R_t$$\frac{(F{A_t}^w + F{A_t}^r)}{P_t}$
    </ul>
    where $x$ is the share of the equity, $\bar{P}$ is the price of assets, superscript F denotes final goods firms and K denotes capital producers.
    
  

### Households 

2 types of households: retirees and workers

1. Retirees (superscript r, born at j and retired at k)

Retirees maximize their recursive utility from consumption and leisure:

<ul>
    $V_t^{rjk}$ = {[($C_t^{rjk}$$)^v$(1 - $L_t^{rjk}$$)^{(1-v)}$]$^\rho$ + $\beta$$\gamma$($V_{t+1}^{rjk}$)$^\rho$}$^\frac{1}{\rho}$
    </ul>
    <ul>
    s.t. $\frac{FA_{t+1}^{rjk}}{P_t}$ = ($\frac{R_t}{\gamma}$)($\frac{FA_t^{rjk}}{P_t}$) + $\frac{W_t}{P_t}$$\xi$$L_t^{rjk}$ - $C_t^{rjk}$ - $T_t$
    </ul>
    where FA denotes financial assets and $\xi$ is the relative marginal product of labor of retirees compared to workers.



2. Workers (superscript w, born at j)

Workers maximize their recursive utility:
<ul>
    $V_t^{wj}$ = {[($C_t^{wj}$$)^v$(1 - $L_t^{wj}$$)^{(1-v)}$]$^\rho$ + $\beta$$[\omega$($V_{t+1}^{wj}$)$+(1 - \omega)(V_{t+1}^{rj}$]$^\rho$}$^\frac{1}{\rho}$
    </ul>
    <ul>
    s.t. $F\frac{A_{t+1}^{wj}}{P_t}$ = ($R_t$)(F$\frac{A_t^{wj}}{P_t}$) + $\frac{W_t}{P_t}$$L_t^{wj}$ - $C_t^{wj}$ - $T_t$
    </ul>
    where $\omega$ is the probability that current worker will remain as a worker in the next period.



### Government

Government collects a lump-sum tax & subsidized firms to reduce distortion from monopolistic competition.

Government's budget constraint:
<ul>
    $\tau$$Y_t$ = ($N_t$ + $N_t^r$)$T_t$
    </ul>
    where $N$ denotes workers and $N^r$ denotes retirees.


### Central Bank

Monetary policy - standard Taylor rule
<ul> 
    $R_{t+1}$ = $R_{ss}$ + 1.5$\pi_t$ + $\frac{0.5}{4}$($\frac{Y_t}{Y_t^F}$ - 1) + $e_t$
    </ul>
    where $R_{ss}$ is the short-term nominal interest rate in stationary population and $Y^F$ is the output in the flexible price equilibrium



### Market equilibria

* aggregate equilibrium conditions
* Market clearing conditions

# Calibration

* Model is solved with quarterly frequency
* Parameter values shown in the table are in quarterly terms

![Screen%20Shot%202020-10-06%20at%202.23.42%20AM.png](attachment:Screen%20Shot%202020-10-06%20at%202.23.42%20AM.png)

# Results

### Properties under Stationary Population

There are 3 versions of a stationary population: 
* (i) a younger economy (low $\gamma$) - the baseline  
* (ii) an older economy (high $\gamma$)
* (iii) no life-cycle economy

#### 1. Values under stationary population

Comparing different life-cycle economies gives us counterintuitive results

* Capital-output ratio is slightly lower and real interest rates are slightly higher in older economy compared to the younger economy
* Does not hold generally
* Under some parametric values, real interest rates do actually become lower in a greyer society (consistent to conventional wisdom)

The central bank should consider demographic structures because natural rate of interest is different across different demographic settings. 

#### 2. Alternative demographic structure (parameters $\gamma$ and $\xi$)

* (increase in $\gamma$) The labor supply of retirees increases, as life expectancy grows. When the average length of retirement is less than 10 years, real interest rate decreases. However, when the average length of retirement is longer than 10 years, the real interest rates rise.
* (increase in $\xi$) As the labor productivity increases, we see higher real interest rates. The retiree's labor supply is now much lower than the worker's labor supply (despite having no difference in relative labor productivity). 

### Dynamic Properties

In this part, we look at the results about whether different demographic structures affect the degree of amplification of impulse responce functions and whether structural shock have asymmetric effects on workers and retirees. Authors consider two types of shocks:
* A technology shock
* A monetary policy shock  
The benchmark model is (iii) no life-cycle economy.  
Tradeoff between substitution and income effects. 

#### 1. Technology shock 

* In the baseline model, a positive shock to the technology, increases the level of output, consumption and investment. As the marginal cost decreases due to the shock, the inflation rate and nominal interest rates decrease, as well as the labor supply because of sticky prices. 
* In life cycle economies responses are similar to the economy with homogeneous agents, but effects are different on workers and retirees. The difference between workers and retirees is smaller under the older life-cycle economy.  Older economy is similar to the no life-cycle economy. 
* With shorter life expectancy of retirees, retirees do not change consumption as much as a result of a technology shock. However, aggregate output and the inflation rate effects become bigger. Due to the benefits from better technology, workers do not have save as much for the retirement. 
* When the productivity of retirees goes up, the difference between workers and retirees is smaller. 

#### 2. Monetary policy shock

* In the baseline model, a tighter monetary policy shock decreases investment, consumption and output. The real wages and marginal cost also go down. Thus, a positive shock to nominal interest rates results into deflation.
* An increase in the nominal interest rates dominates retiree's substitution effects. We see a difference between the responces of retirees and workers. Thus, the central bank faces a policy tradeoff. If the bargaining power in politics is higher for retirees, the nominal interest rates might be biased upwards. In older life cycle economy, the difference between the two groups is smaller.
* With larger life expectancy of retirees, a tightening monetary policy shock still has negative impact on aggregate demand. 
* When the relative labor productivity of retirees goes down, their labor supply is very small.

# Conclusion

* Because retirees rely more on their interest income rather than wage from the labor supply, shocks in the economy have different impacts on heterogeneous agents. 
* The different demographic structures alter the size of the responsiveness to technology and monetary policy shocks that comes from the tradeoff between substitution and income affects.
* Hence, the findings imply that societal aging and life-cycle have significant implications for monetary policy. Thus, the central bank should take into account there considerations.

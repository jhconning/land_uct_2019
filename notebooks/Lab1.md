
# Lab Week 1, Day 1  (Conning)

The following problems explore problems involving Coasean bargaining, property rights insecurity and (mis)allocation similar to examples in class. 

### Problem 1: land (mis)allocation across farms

A village has communal lands. Resident villagers have rights to farm unutilized lands. There are two farmers A and B who each have access to the same production technology. Each unit of output they produce can be sold to traders at a price of $p=1$ per unit.  Land must be cleared before it can be farmed at a cost of $c_l$ per unit. 

Farmer A however has higher status within the village which gives her the right to choose cultivation land first. Village norms establish that she should not use more land than she can profitably farm, but she does have rights of first access and no rent is charged.

Farmer $i$ chooses the amount of land $T_i$ they want to farm to solve:

$$\max_{T_i}  p \cdot F(T_i) - r \cdot T_i $$

where $F(T_i) = 2\cdot A \sqrt T_i $

With abundant land and in the absence of any type of land rental market we take $r$ to simply equal to the cost of clearing land $c_l$.

a) *Solve the farmer's problem to derive an expression for their optimal land demand function $T_i^*(r, p)$:*

b) Assume $A=4$, $c_l =1$ and that the village has a total of $\bar T =100$ units of land.   

*Verify that at these parameter each farmer wants to farm 16 units of land, for a total of 32 units of land. Draw an approximate diagram* 

Since this falls short of total village lands of $\bar T=100$ there is no conflict or congesiton and each farmer gets their preferred allocation.

c) Assume now that improved product market conditions result in a doubling of the price from $p=1$ to $p=2$. 

*How much land does each farmer now want to employ?*

d) Farmer A is given her preferred land allocation first which then leaves farmer B with only $\bar T - T_A^*(c_l,p=2)$ units of land to farm. Farmer B utilizes this amount but it is less than their desired use of $T_B^*(c_l,p=2)$).  

*What is the quantity and the value of output for each farmer under this allocation? What is total output and value?*

e) *Draw an approximate diagram to describe this allocation. *

f) in this now land-scarce economy, *what are the first-order necessary conditions for efficient land allocation?* You can find this by setting up the planner's programming problem. *How would land be allocated?  What is the total quantity and value of output?*

g) *What is the deadweight loss (DWL) associated with the allocation where A gets their preferred land allocation and B only gets what remains?* (hint: how much lower is the value of output compared to an efficient allocation).

*Does this DWL seem large or small  In practice what factors not considered here might make the DWL higher or lower?*

h) Even though farmer A has access to more land and produces more output due to ther higher status, farmer B can offer to pay farmer A to farm less land.  If they bargain to an efficient solution, *how much land does A cede to B and what is the most that farmer B is willing to pay for this? *

*Do you think that this is likely to happen in practice (in the real world, with more villagers)?  What kind of arrangements do you think might arise (or not arise)?* 

i) Suppose we title all land and create a competitive land market. *What would be the equilibrium rental price and land use for each farmer?* (Hint: in the absence of imperfections, the equilibrium rental price should equal the marginal value product of land on either farm at the efficient allocation).  *Does the efficiency of the final allocation depend on who in the village receives title to the land?*  

j) *If the land claims were to be made tradeable and a land market created how should the original claims be distributed?  Compare three stylized scenarios.  In scenario 1 inital land ownership is distributed proportional to the claims they had 'customarily' employed (e.g. farmer A gets the amount of land she profitably employed in c) when she just had to pay the cost of clearing). In scenario 2 each farmer is given and equal share of the land.  In a third scenario the land is declared to be communal owned but the village authority sets up mechanisms to rent out land on a competive basis to the highest bidder and returns land rents earned back to the community by dividing it up equally amongst all villagers.  What are theoretical and practical implications of each of these stylized alternatives in terms of efficiency, equity and political feasibility* 

### Problem 2:  factor intensity adjustment and institutional change

We study production technique choice and 'induced innovation' questions employing an isoquant diagram similar to that used in  Figure 1.2 in Otsuka and Place's [chapter](http://ebrary.ifpri.org/cdm/ref/collection/p15738coll2/id/126296) in the reading for day 1.

![Otsuka-Place](media\Boserup_isoquants.png)

"Initially the population is scarce and land is abundant in areas of vast virgin forests.. Since land is abundant it is cost effective to practice shifting cultivation with sufficiently long fallows... we measure land input in terms of areas 'used' for cultivation, including fallow land..for simplicity the production function is subject to constant returns to scale."

Asume existing production technology can be summarized by a linear-homogenous (i.e. constant returns to scale) production function of the form 

$$F(T, L) = A \cdot T^\alpha \cdot L^{1-\alpha}$$

The abundance of land in the territory and associated high (shadow) wage-rental ratio $\frac{w}{r}$ will lead farmers to choose relatively land-intensive production techniques (with long fallowing).  The cost-minimizing way to produce $q_0$ units of output will be given by: 

$\min r \cdot T + w \cdot L$

subject to 

$ A \cdot T^\alpha \cdot L^{1-\alpha} = q_{0}$

Note that we don't need to actually assume that competitive factor markets operate in the territory for agents to be lead to adopt such cost-minimizing techniques. We only need to assume that village resource allocation mechanisms adapt relative scarcities to adjust techniques to use resources efficiently.  This could be modeled as the solution to a village planner's problem and the the shadow wage-rental $\frac{w}{r}$ would then be measured from $w/r = F_L/F_T$.

The authors refer to the $I_0I_0$ isoquant in the diagram as the unit-isoquant (i.e. $q_0 = 1$).  

a) Show that the first-order conditions for this constrained optimization problem lead to a tangency condition that implies that optimal (cost-minimizing) land-labor intensity will be proportional to the (shadow) wage-rental ratio:

$$\frac{T}{L} = \frac{\alpha}{1-\alpha} \frac{w}{r}$$

Assume for the rest of the problem set that $A=1$ and $\alpha = \frac{1}{2}$  

b) Show that the $q = q_0$ isoquant can be graphed as $T = \frac{q_0^2}{A^2 \cdot L}$.  

c) Use this last result together with the optimal land-labor intensity (tangency) condition to find that the optimal factor demands are:

$$L = \frac{q_0}{A}\frac{1}{\sqrt{w/r}}$$
$$T = \frac{q_0}{A} \sqrt{w/r}$$

Suppose there are $\bar T = 400$ units of land in the territory and $\bar L = 100$ inelastically supplied units of labor. The territory-wide land to labor ratio is therefore $\frac{\bar T}{\bar L}=4$. 

Every farmer has access to the same technology and faces the same relative factor prices $w/r$ each farmer will use the same land-labor intensity and $\frac{T}{L}= \frac{\bar T}{\bar L}=4$ (we are assuming negligible land preparation costs). If this is the case then from the tangency condition above, the equilibrium wage-rental ratio must be $\frac{w}{r} =\frac{\bar T}{\bar L} =4$. 

(Note: As the production function is CRS we can only determine the optimal land-labor ratio on each farm. The equilibrium size of each farm (i.e. what level of land and labor) is indeterminate in neo-classical equilibrium. That's because with CRS the average and marginal cost of production will be the same across all farms. We need local decreasing returns or, same thing, rising marginal costs at the firm level, to determine farm scale.  This does not matter for our present application.)

d) For the reasons just described assume that the wage-rental ratio has risen to $\frac{w}{r} = 4$.  What is the optimal (cost-minimizing T/L) method to produce $q_0 =10$? (hint: the answer is above .. but you should check that with a formula).  Think of this production method as equivalent to point $E_0$ from the Otsuka-Place diagram above.

e) Suppose that the local population and labor force rises from $\bar L =100$ to $\bar L=200$, due perhaps to immigration.  If this economy behaved like an idealized competitive economy (or equivalently, if via other mechanisms resource allocation adjusted to efficiently utilize available resources) what will be the new equilibrium wage-rental ratio?  What is the new land-labor intensity and land and labor use on each farm to produce $q_0=10?$ This corresponds to point $E_0^\prime$ in the diagram.

f) Otsuka and Place argue that with existing traditional technologies less land-intensive production techniques will be associated with shortened fallowing lengths which would over time lead to declining land productivity.   We can associate that here with a reduction in the value of the total factor productivity parameter $A$.  

Suppose that $A$ is reduced from $A=1$ to $A=0.8$. How much more land and labor does a farmer now need to employ to produce the same $q_0 = 10$?

Another potential adaptation to the problem of rising land pressure might be the introduction of new more labor-intensive farming systems (depicted by the introduction of an entirely new more labor-intensive technology associated with isoquant $I_2 I_2$ in the diagram above). For example the introduction of commercial tree crops.  The adoption of such new technologies may however be hampered by existing property relations. For example:

>since usufruct rights are not totally secure and transfer rights are restricted under traditional land tenure institutions, the expected returns to investment may be depressed: those who plant trees may not be able to reap the benefits because of tenure insecurity or an inability to bequeath the property to their desired heirs or to sell the land freely if the need arises (p 43)

Land tenure insitutions may be induced to change through a demand-driven process under customary land tenure rules but, depending on factors such as 

>high costs of investment... poor returns... difficulties in organizing collective action, and high transaction costs or legal restrictions on the choice of property rights institutions may all inhibit innovative institutional responses, resulting in the delay of rehabilitation and continued resource degradation (p43).


### Problem 3: factor markets and land redistribution in a simple farm household model

An unmarried farm laborer, call him Tom, earns income by selling his labor on a competitive wage market.  He values consumption (of maize) and leisure bundles using utility function $u(c,l) = c \cdot l$ where $c$ is his daily maize consumption and $l$ is his daily leisure measured in hours. His daily labor endowment is $\bar L =24$ hours. The market wage rate is $w$ and the price of maize is $p$.

Initially Tom is a landless worker: his only source of income is what he can earn from selling wage labor.  If he chooses to enjoy $l$ hours of leisure his labor supply will be $\bar L - l$ and his wage income $w(\bar L - l)$

Tom chooses consumption and leisure levels to solve: 

$\max_{c,l} \ \ c \cdot l$

subject to

$p \cdot c = w (\bar L - l)$

It is useful to rewrite the budget constraint as:

$p \cdot c + w \cdot l = w \bar L$

which we interpret as saying that Tom purchases maize $c$ and leisure $l$ out of his endowment labor income $w \bar L$.  Each hour of leisure that Tom consumes is priced at its opportunity cost $w$ since an extra hour of leisure is an hour not worked (Tom will not ever work 24 hours because the marginal utility of leisure (including rest) rises very quickly as leisure is driven to zero).

a)	Solve for Tom's maize $c(w,p,I)$ and leisure $l(w,p,I)$ demand functions where here $I=w \cdot \bar L$.

(Hint: For Cobb-Douglas utility functions of the form $x^\alpha y^\beta$, the Marshallian demands will be $x(p_x,p_y,I) =\frac{\alpha}{\alpha+\beta} \frac{I}{p_x}$ and $y(p_x,p_y,I) =\frac{\beta}{\alpha+\beta} \frac{I}{p_y}$ where $I$ is his income.)

b)  Write down an expression for Tom's labor supply function derived from his leisure choice, $H(w,p,I)=\bar L - l(w,p,I)$. 

Is this labor suplly ever backward bending (i.e. does labor supply ever fall with rises in $w/p$)?

d)	Assume that $w = 1$ and $p =1$ measured in dollars.  What is Tom's optimal choice of $c$ and $l$?  How many hours of labor does he supply to the wage market?  What is his total income.

e)	Draw a diagram that approximately represents Tom's optimal consumption-leisure (and labor supply) choices (leisure on horizontal). Follow the labeling from the example we saw in class. 

Assume that Tom discovers he has farming abilities and a land reform program transfers a 1 hectare plot of land to him.  By applying his own or hired labor $L$ to this plot he can produce maize through the production function $F(L)=4\sqrt L$ , which he can then sell or consume.

There is no land rental market (either because it's banned under the terms of the land reform or because of high transactions costs).

f)	Tom's profit as a farm producer are given by  $\Pi (w,p) = p \cdot F(L) - wL$.  If $w=1$ and $p=1$ what is Tom's profit maximizing labor input choice L*?   How much profit does he earn?

g)	Tom's own labor and hired labor are perfect substitutes in production.  Solve for his new optimal consumption and leisure choice and labor supply now that he has this maximized profit income (Hint: Tom first maximizes farm profits via own and/or hired labor; his total income is $\Pi(w,p) + w\bar L$. 

h)	What has been the impact of the land reform on Tom's total supply of labor?  Does he increase or decrease leisure? 

i) At this wage rate and price ($w=p=1$) you should find that Tom is a net supplier of labor to the wage market. That is to say, he first farms his own plot at profit maximizing scale that you found above and then turns to the labor market supply the additional hours he wants to to generate income (Working more hours on his own farm would offer a lower marginal return compared to the market wage due to the diminishing marginal value product of labor).

j) Suppose that Tom's outside his own farm is as a harvest worker in the commercial cash crop sector (remember he grows maize). A sudden collapse in the commercial sector (say due to unusual weather patterns) leads to a sudden very large drop in labor demand from that sector and a sharply lower equilibrium wage of w=1/2. 

How does Tom's income, consumption and utility respond in this new depressed wage environment?

Tom's income, consumption and utility responded if he had remained a landless worker?

### Hi there 👋

![](https://visitor-badge.glitch.me/badge?page_id=chauncygu)

- 🔭 I’m currently working on safe reinforcement learning theory and its applications in robotics.


<img align='right' src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="230">


<!-- **chauncygu/chauncygu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on safe reinforcement learning theory and its applications in robotics.
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ... -->


**Q2** More discussion on the special multi-agent properties (uncommon for single-agent RL) in the safety problem would be appreciated. For example, what if agent A is caused harm by agent B, rather than itself?

> **A2** Indeed, our theory is developed so that the agent can recover from its harm by itself. In the above-described scenario, our methods would make agent A escape the dangerous situation and find an alternative behaviour. It is most likely, however, that in such a situation agent B is at risk too (e.g., when two cars crash). Thus, both agents would alter their actions to reach safety. In multi-agent settings, each agent needs to consider each other safety and reward, in single-agent settings, the ego agent just needs to consider itself reward and safety. For example, in our problem formulation,  although the action $a_t^i$ of agent $i$ does not directly influence the costs $\{C^k_j(s_t, a_t^k)\}_{j=1}^{m^k}$ of other agents $k\neq i$, the action $a^i_t$ will implicitly influence their total costs due to the dependence on the next state $s_{t+1}$. More particularly, the setting of implicit influence is suitable to real-world applications, and this formulation realistically describes multi-agent interactions; an action of an agent has an instantaneous effect on the system only locally, but the rest of the agents may suffer from its consequences at later stages. For example, consider a car that crosses on the red light; although other cars may not be at risk of riding into pedestrians immediately, the induced traffic may cause hazards soon later.


$\{C^k_j(s_t, a_t^k)\}_{j=1}^{m^k}$ of other agents $k\neq i$, 
the action $a^i_t$ will implicitly influence their total costs due to the dependence on the next state $~$      $Q_{t+1}$

s<sub>t+1</sub>

cause hazards soon late $Q_{t+1}$

$s_{111}$

$a+\underbrace{b+c}_{1.0}+d$



<!-- [![trophy](https://github-profile-trophy.vercel.app/?username=chauncygu&column=7)](https://github.com/chauncygu)

| <img align="center" src="https://github-readme-stats.vercel.app/api?username=chauncygu&show_icons=true&hide_border=true" /> | <img align="center" src="https://github-readme-streak-stats.herokuapp.com?user=chauncygu&hide_border=true&date_format=M%20j%5B%2C%20Y%5D&ring=7EDDCF&fire=7EDDCF" /> |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
-->
![visitors](https://komarev.com/ghpvc/?username=chauncygu&color=brightgreen) 

<!-- ![](https://visitor-badge.glitch.me/badge?page_id=chauncygu) -->

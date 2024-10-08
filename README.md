# Introduction

My research focuses on uncertainty modeling using ML and simulation models.
This includes uncertainties in wind engineering, catastrophe modeling and uncertainties in structural models of buildings and bridges.

<h3> Research Profile </h3> 
      <ul>  
        <li> <a href="https://scholar.google.com/citations?user=-Wiy3ksAAAAJ&hl=en&oi=ao"> Google Scholar Profile </a>  </li>  
        <li> <a href="https://orcid.org/0000-0003-0485-2545"> Orcid Profile </a>  </li>
      </ul>


<table>
  <tr>
    <td width="50%">
      <img src="https://www.site-shot.com/cached_image/0wgcIITgEe-pggJCrBEAAg" width="800" />
    </td>
    <td width="50%">    
      <h3> Direct Links to Selected Publications </h3> <!-- Add your title here -->
      <ul>
        <li> <a href="https://www.sciencedirect.com/science/article/abs/pii/S0141029616317540"> Bayesian Modeling for Residential Buildings </a>  </li>
        <li> <a href="https://www.mdpi.com/2674-032X/2/1/6"> Wind Vulnerability Simulations </a></li>
        <li> <a href="https://www.sciencedirect.com/science/article/abs/pii/S2352710215000157"> Bayesian Roof Cover modeling </a></li>
        <li> <a href="https://www.sciencedirect.com/science/article/abs/pii/S2352710217300980"> Statistical Corrosion Detection </a> </li>
        <li> <a href="https://www.sciencedirect.com/science/article/abs/pii/S0141029615004071"> Bridge Damage Prediction </a> </li>
        <li> <a href="https://www.mdpi.com/1996-1073/16/3/1207"> Wind Farm Risk </a> </li>
        <li> <a href="https://www.researchgate.net/profile/Gholamreza-Amirinia/publication/301891562_Effect_of_different_hurricane_spectrums_on_wind_turbine_loads_and_responses/links/5a04fc19aca2726b4c73ad70/Effect-of-different-hurricane-spectrums-on-wind-turbine-loads-and-responses.pdf"> Wind Turbine Tower </a> </li>
      </ul>
    </td>
  </tr>
</table>



### 1. Catastrophe Model

A typical cat modelling approach follows four important steps, which are 1. Quantification of hazard, 2. Exposure database, 3. Vulnerability of the portfolio buildings and 4. Financial loss based on repair cost and downtime.

Hazard module helps to quantify the intensity of the peril at any location under study.

Exposure database system maintains attributes of portfolio buildings which are targets of peril.

Vulnerability module provides probabilistic loss ratios for the building using the intensity of peril at the specific location.

Loss module converts the loss ratios and incorporates policy specification for different properties to determine actual dollar loss.

This research focuses on modeling dollar losses in residential and commercial buildings using a simulation based approach.

The vulnerability model developed in this study (Alduse et al, 2017), is flexible and addresses multiple building archetypes. For example, residential, retail, schools, warehouses, offices and hospitals can be easily modeled to obtain losses at different wind speeds, debris conditions and rainfall intensities. Furthermore, damage function suite can be developed (by running parallel simulations on cluster) for a variety of insured properties.

Highlights of the model
Available in open source (Octave) and Matlab platform.
Based on latest research in wind induced losses (as of 01/2022) - wind, rain and debris; incorporates latest findings from FEMA P58 (Seismic) in building model.
Captures more than 25 variables of building and environment.
Easy to edit and explore influence of primary and secondary modifiers/attributes.
Results validated using published articles and industry data.

<a href="https://www.sciencedirect.com/science/article/abs/pii/S0141029616317540"> Bayesian Modeling </a>

<a href="https://www.mdpi.com/2674-032X/2/1/6"> Wind Vulnerability </a>


### 2. Bridge Fatigue
In order to estimate wind-induced fatigue damage, most methods use the probability density functions of wind speed and direction. Conventional approaches assume that these functions are error-free and provide a single estimated damage value. However, the estimated damage may contain significant errors because the probability density functions are generally inexact, and the parameters for the functions rely on limited measured data. We propose a Bayesian approach to determine the fatigue damage while considering the uncertainties in the probability model and the parameter. The proposed approach provides a distribution of damage values, which enables more comprehensive analysis of fatigue damage using bounds and exceedance probability. The approach is applied to the estimation of fatigue damage of long-span bridges.

<a href="https://www.sciencedirect.com/science/article/abs/pii/S0141029615004071"> Bridge Fatigue Uncertainty</a>

### 3. Roof cover

Fragility modeling is a commonly used approach to quantify the risk of a structure subjected to high winds. In order to overcome a limitation of conventional fragility models where the performance of the roof cover is assumed to be fixed, we propose a new framework for obtaining the fragility of roof covers under high winds. The approach models the capacity related terms as functions rather than fixed values. Therefore, it can describe gradual increase of failure probability as the roof cover degrades over time. The parameters for the capacity functions are obtained from sensor measurements. In order to overcome the uncertainties associated with the limited measurements, a Bayesian approach is employed. 

<a href="https://www.sciencedirect.com/science/article/abs/pii/S2352710215000157"> Roof Cover </a>

### 4. Corrosion detection

A method is proposed to detect hidden corrosion in metal roofing shingles. The method involves three components: 1) application of a simple heating source that can cause a temperature discrepancy between uncorroded shingle and corroded shingle, 2) acquisition of temperate data using a digital infrared camera, and 3) data analysis that can help us locate hidden corrosion. Experiments were conducted to test the effectiveness of the proposed method. Samples with different material, thickness, and surface coating were subjected to accelerated corrosion on one half of the interior surface. The other half of the interior surface was left uncorroded as a baseline. Using a digital infrared camera, thermal images were collected and analyzed. Two different data analysis methods were proposed to detect the corrosion.

<a href="https://www.sciencedirect.com/science/article/abs/pii/S2352710217300980"> Corrosion Detection </a>

### 5. Wind farm risk

Wind turbines as the structures which are designed to harness huge amount of wind energy are subjected to special loads such as high winds and hurricanes because of their heights. Hurricane wind spectrums and amount of energy content is one of the important parameters that make hurricane winds different from regular high winds. In this draft paper, we investigate how different spectrums of hurricane winds influence the wind turbine response, using a simplified wind turbine structure. Two different approaches for hurricane wind spectrums are cited and time 30 series based on each of these approaches are generated. In addition, 30 time series based on regular high wind spectrum are generated and applied on the structure. The results show that, for structure with high amount of natural frequency, the hurricane spectrum with higher energy in high frequencies part has more effect on the structure so it would be more conservative to use these spectrums for design.

<a href="https://www.mdpi.com/1996-1073/16/3/1207"> Wind Farm Risk 1 </a>

<a href="https://www.researchgate.net/profile/Gholamreza-Amirinia/publication/301891562_Effect_of_different_hurricane_spectrums_on_wind_turbine_loads_and_responses/links/5a04fc19aca2726b4c73ad70/Effect-of-different-hurricane-spectrums-on-wind-turbine-loads-and-responses.pdf"> Wind Farm Risk 2 </a>

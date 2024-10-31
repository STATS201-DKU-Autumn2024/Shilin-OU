# Global Energy Scenario Modeling Dataset
  The dataset serves as a vital resource for analyzing the influence of capital costs on energy investments across various scenarios and regions. It encompasses data from three prominent models: Integrated Model to Assess the Global Environment, Integrated Model to Assess the Global Environment, and World Induced Technical Change Hybrid Model, along with key metrics such as maximum and minimum weighted average cost of capital (WACC). By tracking these variables over time, researchers can uncover patterns that highlight how capital costs affect investment decisions in renewable energy.

  This analysis is crucial for understanding the financial barriers or incentives that influence sustainable energy transitions. By employing machine learning techniques, researchers can develop models that predict how fluctuations in economic conditions or policy changes impact WACC, thereby guiding investment strategies. Ultimately, this research can provide actionable insights for policymakers and investors, facilitating informed decisions that promote sustainable development and optimize energy resource allocation in the face of evolving economic landscapes.

## References
Calcaterra, M., Reis, L. A., P. Fragkos, T. Briera, de, S., Egli, F., Emmerling, J., Iyer, G., Mittal, S., Polzin, J., Sanders, L., Schmidt, T. S., A. Serebriakova, Steffen, B., van, Vuuren, van, Waidelich, P., & M. Tavoni. (2024). Reducing the cost of capital to finance the energy transition in developing countries. Nature Energy. https://doi.org/10.1038/s41560-024-01606-7
## Notes
detaled data in 
## Data Dictionaries
### Table 1: Global Energy Scenario Modeling Dataset Data Dictionary
| Variable Name | Definition                                                                                                                   | Range (Date & Value)                  | Frequency                                                                                          |
|---------------|------------------------------------------------------------------------------------------------------------------------------|---------------------------------------|----------------------------------------------------------------------------------------------------|
| `Region`      | Geographic area where the data is collected (e.g., Africa, Europe). Represents regional focus and context of energy cost analysis. | Africa, Europe, etc.                 | N/A                                                                                                |
| `Scenario`    | Modeling scenarios providing different possible futures (e.g., 'CoC-reference', 'NDC'). These scenarios help in assessing varying economic and policy impacts on energy costs. | 'CoC-reference', 'NDC'               | N/A                                                                                                |
| `Variable`    | The specific type of energy source or production method (e.g., 'Onshore', 'Offshore'). Useful for distinguishing the cost dynamics of different energy technologies. | 'Onshore', 'Offshore'                | N/A                                                                                                |
| `Year`        | Year of the data point, which can range from historical to projected values. This temporal dimension aids in trend analysis over time. | 2020 - 2100                          | Annual data points across multiple years                                                           |
| `scengroup`   | Scenario grouping that shares common characteristics or assumptions, helping to categorize analyses under similar policy frameworks. | 'NDC', other categories              | N/A                                                                                                |
| `IMACLIM`     | Model output from the Integrated Model to Assess the Global Environment (IMACLIM), focusing on macroeconomic impacts under environmental policies. | 0.0000 - 1.0000                      | Represents a range of environmental impact measures                                                |
| `IMAGE`       | Model output from the Integrated Model to Assess the Global Environment (IMAGE), emphasizing interactions between energy, land use, and climate policies. | 0.0000 - 1.0000                      | Projections for different energy-land use interactions                                             |
| `WITCH`       | Model output from the World Induced Technical Change Hybrid Model (WITCH), examining the role of technological changes and costs in achieving sustainable growth. | 0.0000 - 1.0000                      | Model outputs assessing technology-driven impacts on sustainability                                |
| `maxwacc`     | Maximum weighted average cost of capital, representing the upper bounds of financing costs for investments, critical for high-risk evaluations. | 0.0000 - 1.0000                      | Annual maximum WACC values that determine the cost ceiling for energy investments                   |
| `minwacc`     | Minimum weighted average cost of capital, indicating the lowest financing costs, essential for assessing the feasibility of low-risk investments. | 0.0000 - 1.0000                      | Annual minimum WACC values, representing baseline capital costs for viable projects                |

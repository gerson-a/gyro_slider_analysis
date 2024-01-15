# Portfolio Project: Slider Analysis (2022-2023)
A comparison of various slider types thrown by pitchers across the 2022 and 2023 MLB regular seasons.

# Introduction

A gyro slider, or gyro (as I'll refer to it for the rest of this project) is a slider that uses large amounts of gyroscopic spin -- the spin imparted on a bullet or a football, for example -- to stabilize the flight path of the pitch. This gyroscopic spin runs perpendicular to the path of the ball as it heads towards home plate, such that little to no horizontal or vertical movement is generated. This is unlike a conventional slider, which uses sidespin (also referred to as transverse spin) to generate large horizontal movement.

In this project, I used Statcast data from the 2022 and 2023 seasons to compare the effectiveness of gyros in relation to sweepers and traditional sliders and identify what role the gyro plays in a pitcher's arsenal.

# Summary of Insights
- Sweepers performed best in wOBA and xwOBA, with the 50th percentile sweeper being roughly 2% more effective in each statistic. Despite the increased popularity and notiriety of the pitch, it remains the most effective slider type with regards to these core performance metrics.
    
- Gyros and sweepers had similar CSW% (called strikes + whiffs rate), with each scoring roughly 31% CSW at the 50th percentile level. Although the gyro has a completely different movemement profile from a sweeper, the pitch is able to beat hitters in the most important category with the same consistency. Pitchers who are unable to make effective use of sweepers should consider a gyro as a replacement in their arsenals.
    
- The most effective pitchers with gyros in their arsenals throw four-seam fastballs nearly 5% more frequently than the total pitcher population, as well 5% fewer sinkers and cutters with a slight increase in curveball usage. These pitchers emphasize a north-south approach with their arsenal, whereas the total pitcher pool incorporates more east-west movement. Pitching coaches should recommend gyros to pitchers with effective four-seams and curves who are in need of a 3rd offering.
    
- The best gyro pitchers tend to release the ball from higher arm slots closer to the body. These high and tight release points make it easier for the pitcher to stay behind the ball and generate the necessary spin for an effective gyro. Taller pitchers with high arm slots should consider an arsenal that emphasizes north-south movement to make best use of their deliveries.

# Technical Analysis
Samples of bar graphs used for slider comparison and arsenal insights are below. More detailed analysis is contained in the Python workbook in this repository.

![est_woba comp](https://github.com/gerson-a/gyro_slider_analysis/assets/142946842/4cd40d77-34de-4e06-a667-7c859a34d9c7)

![csw comp](https://github.com/gerson-a/gyro_slider_analysis/assets/142946842/540dc240-5fc4-44fa-bae2-0a1d95da6d80)

<img width="560" alt="percentage thrown" src="https://github.com/gerson-a/gyro_slider_analysis/assets/142946842/98e54e1e-82ac-40fd-8f39-49449c2a5e30">



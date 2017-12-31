# 3D-Material
Comparison of the mechanical properties of 3D printing material from various companies

Ideas: 
- 2D bar graphs in different planes https://matplotlib.org/gallery/mplot3d/bars3d.html#sphx-glr-gallery-mplot3d-bars3d-py
- distribution analysis to see how different the mechanical properties are
- have the st dev on a separate sheet/data frame so can call the std for each property (just have 0s for those without)

Issues with comparing material properties: 
- Even within the same company, they use different standards for reporting their values (for example the 3D Systems’ MJP materials use ASTM vs Next Dent DLP materials use ISO)
- ASTM D790, ISO 10477:2003, ISO 20795-2:2013 ARE ALL USED FOR FLEXURAL MODULUS! 
- Companies for the most part don't mention if the Tensile strength is at the yeild point or break point. Then you have Carbon that has both..so which to use?! I am going to use the Tensile strength at yeild and can change it if learn better.
- Water sorption, most don't state time. Carbon states 24 hrs and long term %s. I will use the long term one.
- Using different units for IZOD impact strength results


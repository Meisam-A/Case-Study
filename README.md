# Case-Study

- Download the repository "Case-Study" and add your data-set in both subfolders (2D Visualization and 3D Visualization)
- Case Study folder contain 2 subfolders (2D & 3D Visulization of Data) each of which contain implementation(ipynb formt) and output results(HTML/PNG format) 
- To run the project, first, it is necessary to install all the following Packages which enable us to implement different approaches:
(Since I used Anaconda, the installation commands are based on it)
  1. Networkx: conda install -c anaconda networkx
  2. Pydot: conda install -c anaconda pydot
  3. Graphviz: conda install -c anaconda graphviz
  4. Plotly: conda install -c plotly plotly 
  5. Chart Studio: conda install -c plotly chart-studio
  6. Mpld3: conda install -c conda-forge mpld3 
- After installation of required packges, open the source codes (2D_Visualization.ipynb / 3D_Visualization.ipynb), follow the instruction, and run the cells to obtain desired results
- To explain better the implementation, comments are added on each cell as well.

## Task 1:
- Data Visualization is implemented in different approaches for each 2D and 3D Visualization 
  #### 2D Visualization:
  1. **First Approach:** Interactive Network by exploiting Networkx and D3
  2. **Second Approach:** 2D Networks in 5 different layouts using only Networkx toolkits
    - Pydot and Graphviz Layout 
    - Planar Layout
    - Spiral Layout
    - Circular Layout
    - Spring Layout
  #### 3D Visualization:
   - This visualization is implemented for only 2 different layouts which support 3D dimension(Spring Layout / Circular Layout )
   1. **First Approach:** By exploiting Plotly Library
   2. **Second Approach:** By exploiting mplot3d toolkit (Using linear scaling to scale the size of each node proportional to the number of edges adjacent to a single node)
 
 ## Task 2:
- Although I am not an expert with Web Application Development, I tried to do my best to fulfill the whole project.
- I embedded my visualization on my Plotly Chart Studio account ("https://chart-studio.plotly.com/~Meisam-Asgari/1") and deployed it along with some other obtained results in a free hosting service with "https://masgarioe.wixsite.com/website" URL.

#### Finally, I hope the implementations have been  consistent with your expectation

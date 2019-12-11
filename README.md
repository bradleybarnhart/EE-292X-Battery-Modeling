# ee292x
Machine Learning project for Autumn 2019 EE292X at Stanford

## Data

[rawdata](rawdata): original data dropbox links and decriptions provided by Stanford ECL (along with cell datasheet)

[data](data): cleaner data organizaed by temperature and discharge cycle

The data in [data](data) is also downloadable as a zip file on [Google Drive](https://drive.google.com/file/d/1ry2kAellwxSpw0W4s4LuJZxe__ECa64I/view?usp=sharing).

## Code

[goal1](goal1.ipynb): functions load and clean data in a dataframe, train models with current and SoC as inputs, validate on randomly held out cycles, and visualize results

[goal2](goal2.ipynb): functions load and clean data in a dataframe; train models with current and SoC as inputs; train models with current, SoC, and temperature as inputs; validate on held out US06 cycles; and visualize results
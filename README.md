# **Land Parcel**

## **Purpose of the Project**
This project is designed to optimize land parcel selection to  **maximize carbon storage**  within budget, adjacency, and area constraints. The project will accomplish its goal with linear programing and geospatial data processing.

## **Setup Instructions**
### **1. Create a Virtual Environment**
Set a virtual environment for managing dependencies. One can be set with the commands:

```bash
python -m venv env
source env/bin/activate  # On macOS/Linux
env\Scripts\activate    # On Windows
```

### **2. Install Dependencies**
With the provided requirement.txt file, the needed Python libraries can be installed with a command:

```bash
pip install -r requirements.txt
```

or:

```bash
pip install geopandas pulp matplotlib numpy pandas pyproj
```

## **Requirements (requirements.txt)**
```
geopandas
matplotlib
numpy
pandas
pyproj
pulp
```

## **References**
- **Geospatial Processing:** [GeoPandas Documentation](https://geopandas.org/)
- **Linear Programming:** [PuLP Documentation](https://coin-or.github.io/pulp/)
- **GLPK Solver:** [GNU Linear Programming Kit](https://www.gnu.org/software/glpk/)


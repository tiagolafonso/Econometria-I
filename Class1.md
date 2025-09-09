# Class 1 - Data Analysis in Excel

## Data Collection

### **Data Source**
**WDI - World Development Indicators**  
🌐 https://databank.worldbank.org/source/world-development-indicators

---

### **Selected Countries**
| Country | Code |
|---------|------|
| 🇩🇪 Germany | DEU |
| 🇫🇷 France | FRA |
| 🇧🇪 Belgium | BEL |

---

###  **Variables**
```
    GDP (current US$)
    GDP deflator (base year varies by country)
    Tax revenue (% of GDP)
    Population, total
    Mobile cellular subscriptions (per 100 people)
```

---

## Proposed Exercises

### **Exercise 1** 
Calculate the deflator for the base year **2015** for each country

### **Exercise 2** 
Calculate the GDP at **2015** prices for each country

### **Exercise 3** 
Chart the evolution of GDP per capita variation and subscriptions over time *(for one country only)*

### **Exercise 4** 
Is there any relationship between GDP per capita and subscriptions? *(for each country)*

### **Exercise 5** 
Calculate the two statistical moments for all variables *(France only)*
### **Exercise 6** 
Check for the existence of **outliers** for each variable *(France only)*

#### **Formulae for Outlier Detection**

$$\boxed{IQR = Q3 - Q1}$$

$$\boxed{Lower\;Limit = Q1 - 1.5 \times IQR}$$

$$\boxed{Upper\;Limit = Q3 + 1.5 \times IQR}$$
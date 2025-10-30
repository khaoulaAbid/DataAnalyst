# Importation des librairies
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Chargement des données
df = pd.read_csv('data/nom_du_fichier.csv')

# Aperçu des données
print(df.head())

# Visualisation simple
sns.histplot(df['colonne_interessante'])
plt.title('Distribution de la variable')
plt.show()

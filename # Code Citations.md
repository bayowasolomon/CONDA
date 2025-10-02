# Code Citations

## License: MIT
https://github.com/thirteenfoil8/simulateur_choix/tree/5d2a964df3dab678567455e2f5be37aba825abf1/src/simulateur_choix/script/gaz.py

```
],
    'min_samples_split': [2, 5, 10],
    'min_samples_leaf': [1, 2, 4]
}

rf = RandomForestRegressor(random_state=42)
grid_search = GridSearchCV(estimator=rf, param_grid=param_grid, cv=3, n_jobs=-1,
```

from sklearn.metrics import r2_score, mean_absolute_error, mean_squared_error
from imblearn.over_sampling import SMOTE


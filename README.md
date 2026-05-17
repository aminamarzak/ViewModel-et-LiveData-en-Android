# ViewModel-et-LiveData-en-Android

Objectifs
Comprendre en profondeur pourquoi une variable classique est perdue à chaque rotation d’écran (changement de configuration).
Voir concrètement la limite de onSaveInstanceState() (ancienne méthode).
Maîtriser ViewModel (survit automatiquement à la destruction/re-création de l’Activity) + LiveData (lifecycle-aware : met à jour l’UI seulement quand l’Activity est active).
Découvrir les concepts internes : LifecycleOwner, Observer, ViewModelStore, MutableLiveData vs LiveData, setValue vs postValue.
Tester des scénarios réels : rotation multiple, changement de thème, kill processus (process death), thread background.
Appliquer les meilleures pratiques Android 2026 (Jetpack 2.10.0 stable).

<img width="356" height="663" alt="image" src="https://github.com/user-attachments/assets/8399e153-9ee3-4490-86ce-e29591c164de" />



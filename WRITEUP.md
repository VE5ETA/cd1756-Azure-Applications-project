# Write-up Template

# It's recommended to read this pdf file. [Projects summary](https://github.com/VE5ETA/cd1756-Azure-Applications-project/blob/main/screenshots/mousafirstproject.pdf)

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*

| Costs | Case | Points |
| ----------- | -----------  | -----------|
| VM | Expensive  | **0** |
| App Service | Cheap   | **+1** |

```One point goes to the app service for being the best fit.```

| scalability | Case | Points |
| ----------- | -----------  | -----------|
| VM | scalable  | **0** |
| App Service | scalable [^1]   | **0** |

[^1]: App Service have constraints in scalability compared to VM.

```No point to either of them because scalability is not a concern; it's not a big website.```

| availability | Case | Points |
| ----------- | -----------  | -----------|
| VM | good  | **+1** |
| App Service | best   | **+2** |

```Two points go to App Service for less concern about availability because you don't use the whole OS; instead, Azure will help you and manage all the OS stuff.```
```This will lead to less downtime due to development mistakes.```

| workflow | Case | Points |
| ----------- | -----------  | -----------|
| VM | Bad  | **0** |
| App Service | Better   | **+2** |

```VM will take a lot of your time configuring and maintaining the OS compared to App Service, which takes way less time; this will make you spend the time on the important stuff.```


- *Choose the appropriate solution (VM or App Service) for deploying the app*

|  Points | |
| ----------- | -----------|
| VM |  **1** |
| App Service   | **5** |

 ```As you can see, App Service will be the best choice for our project as it's the best fit.```





### Assess app changes that would change your decision.

 **If this project was for a big publishing company, as they will have more visitors to the website, this definitely will make me review my choices.**

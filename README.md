# Shan's HELM Chart Repository

1. Create a new folder "public-helm-charts"  
2. cd public-helm-charts  
3. Create new rpublic repository in Github (e.g., my-helm-charts)  
4. Clone this projet in your local ( e.g, git clone https://github.com/Shanmugavel/my-helm-charts.git)  
5. cd my-helm-charts  
6. Create a new directory named "charts" (e.g., mkdir charts)  
7. cd charts  
8. Create helm chart directory ( e.g., helm create rest-poc-helm) 
9. Update values.yaml, Chart.yaml & yaml files inside templates fodler as per application need  
10. Navigate back to "my-helm-charts" directory ( e.g., cd ..)  
11. Creae robots.txt to stop crawlers from crawling (e.g., echo -e “User-Agent: *\nDisallow: /” > robots.txt)  
12. Create Helm package (e.g, helm package charts\rest-poc-helm) to create tgz file  
13. Create inex.yaml file (e.g., helm repo index --url https://shanmugavel.github.io/my-helm-charts .)  
14. Add all the files to git and push the repository to Github  
15. Add our repo to Helm ( e.g., helm repo add shan-helm-repo https://shanmugavel.github.io/my-helm-charts/)  
16. Searc and verify our chart is available ( e.g., helm search repo shan-helm-repo) 

## Actual command and their outpu can be viewed in Reference.txt file  

# Screenshots (Additional Screensots are in the directory as mentioned).
# NB: I used CircleCI for Continuous Intergration and not Travis.
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed
<img width="849" alt="Screenshot(397)" src="https://github.com/TebogoYungMercykay/Project-3----ALX-T--Cloud-Developer-Nanodegree-Program/blob/main/screenshots/Screenshot%20(397).png">
* GitHub repository’s settings showing your CircleCI webhook (can be found in Settings - Webhook)
<img width="849" alt="Screenshot(327)" src="https://github.com/TebogoYungMercykay/Project-3----ALX-T--Cloud-Developer-Nanodegree-Program/blob/main/screenshots/Screenshot%20(427).png">
* Circle CI showing a successful build and deploy job
<img width="849" alt="Screenshot(383)" src="https://github.com/TebogoYungMercykay/Project-3----ALX-T--Cloud-Developer-Nanodegree-Program/blob/main/screenshots/Screenshot%20(383).png">

## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
<img width="849" alt="Screenshot(393)" src="https://github.com/TebogoYungMercykay/Project-3----ALX-T--Cloud-Developer-Nanodegree-Program/blob/main/screenshots/Screenshot%20(393).png">
* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
<img width="849" alt="Screenshot(419)" src="https://github.com/TebogoYungMercykay/Project-3----ALX-T--Cloud-Developer-Nanodegree-Program/blob/main/screenshots/Screenshot%20(419).png">
* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
<img width="849" alt="Screenshot(418)" src="https://github.com/TebogoYungMercykay/Project-3----ALX-T--Cloud-Developer-Nanodegree-Program/blob/main/screenshots/Screenshot%20(418).png">
* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
<img width="849" alt="Screenshot(436)" src="https://github.com/TebogoYungMercykay/Project-3----ALX-T--Cloud-Developer-Nanodegree-Program/blob/main/screenshots/Screenshot%20(436).png">

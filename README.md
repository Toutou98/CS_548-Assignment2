# CS_548-Assignment2
## csd4054

---

### Task 1
	* a)
		
			kubectl apply -f task1.yaml
			
		![1](task1/1.JPG)

	* b)
	
			kubectl port-forward nginx-pod
			
		![2](task1/2.JPG)
		
	* c)
	
			kubectl logs nginx-pod
			
		![3](task1/3.JPG)
		
	* d)
			
			kubectl exec -it nginx-pod  -- //bin//sh
			
		![4](task1/4.JPG)
		![5](task1/5.JPG)
		![6](task1/6.JPG)
		
	* e)
	
			Μεταφορά αρχείου από το container στον τοπικό υπολογιστή:
			kubectl cp nginx-pod:usr/share/nginx/html/index.html ./index.html
			
			Μεταφορά αρχείου από τον τοπικό υπολογιστή στο container:
			kubectl cp ./index.html nginx-pod:usr/share/nginx/html/index.html
			
		![7](task1/7.JPG)
		![8](task1/8.JPG)
		
	* f)
	
			kubectl delete -f task1.yaml
			
		![9](task1/9.JPG)
		
		
### Task 2
			

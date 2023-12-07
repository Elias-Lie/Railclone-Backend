TODO:
 - Check user authentication
    - More efficient with less data not full struct anymore
 - Use structured logging slog
 - Change env_var from input to image specific struct 

 kubectl port-forward service/mamamia-service 31153:5432
 panic: Service "deployment-1-user-3-service" is invalid: spec.ports[0].nodePort: Invalid value: 33000: provided port is not in the valid range. The range of valid ports is 30000-32767

 user struct register ouput not sorted

# npci_redis

# Install Redis
https://redis.io/topics/quickstart 

# Install Redis on Windows
### Make sure WSL Installed on windows 

# Follow steps below

# Run bash

bash

#Update apt-get 
sudo apt-get update

# Install redis -server
sudo apt-get install redis-server

# Check cli version
redis-cli -v

#Start redis server
sudo service redis-server start

# Access Redis shell 
redic-cli 

#EnableCashe in springboot main file

@SpringBootApplication
@EnableCaching
public class SpringbootRedisCacheApplication {

	public static void main(String[] args) {
		SpringApplication.run(SpringbootRedisCacheApplication.class, args);
	}

}

# Yaml configuration
Refer application.yml file

#Enable Cashe in controller file
Class EmployeeController 

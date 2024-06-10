

1. docker ps
   # List all running containers.

2. docker ps -a
   # List all containers, including stopped ones.

3. docker run <image>
   # Run a new container from a specified image.

4. docker start <container_id>
   # Start a stopped container.

5. docker stop <container_id>
   # Stop a running container.

6. docker restart <container_id>
   # Restart a container.

7. docker pause <container_id>
   # Pause a running container.

8. docker unpause <container_id>
   # Unpause a paused container.

9. docker rm <container_id>
   # Remove a stopped container.

10. docker rm -f <container_id>
    # Forcefully remove a running container.

11. docker exec -it <container_id> <command>
    # Execute a command inside a running container interactively.

12. docker logs <container_id>
    # Fetch logs of a specific container.

13. docker inspect <container_id>
    # Display detailed information about a container.

14. docker stats
    # Display real-time usage statistics of containers.

15. docker images
    # List all locally available images.

16. docker pull <image>
    # Pull an image from a registry.

17. docker rmi <image_id>
    # Remove a specific image.

18. docker build -t <tag_name> <path>
    # Build a Docker image from a Dockerfile in the specified path.

19. docker tag <image_id> <new_tag>
    # Tag an image to give it a new name and optionally a new tag.

20. docker build <path>
    # Build an image from the Dockerfile in the current directory.

21. docker build -f <Dockerfile_path> -t <tag_name> <context>
    # Build an image using a specified Dockerfile, tag, and build context.

22. docker build --pull
    # Always attempt to pull a newer version of the base image.

23. docker build --no-cache
    # Build without using cache.

24. docker build --network <network_mode>
    # Set the networking mode for the build.

25. docker login
    # Log in to a Docker registry.

26. docker logout
    # Log out from a Docker registry.

27. docker push <image_name>
    # Push an image to a registry.

28. docker pull <image_name>
    # Pull an image from a registry.

29. docker search <term>
    # Search for an image on Docker Hub.

30. docker network ls
    # List Docker networks.

31. docker network create <network_name>
    # Create a new Docker network.

32. docker network connect <network_name> <container_id>
    # Connect a container to a network.

33. docker network disconnect <network_name> <container_id>
    # Disconnect a container from a network.

34. docker volume ls
    # List Docker volumes.

35. docker volume create <volume_name>
    # Create a new Docker volume.

36. docker volume inspect <volume_name>
    # Display detailed information about a volume.

37. docker volume rm <volume_name>
    # Remove a Docker volume.

38. docker-compose up
    # Create and start containers defined in a docker-compose.yml.

39. docker-compose down
    # Stop and remove containers created by docker-compose up.

40. docker-compose logs
    # View output from containers started by docker-compose up.

41. docker-compose build
    # Build or rebuild services defined in the docker-compose.yml file.

42. docker run --cpu-shares <value>
    # Specify the CPU shares for a container.

43. docker run --memory <value>
    # Set a memory limit for a container.

44. docker update --cpus <value> <container_id>
    # Update CPU quota for a running container.

45. docker update --memory <value> <container_id>
    # Update memory limit for a running container.

46. docker swarm init
    # Initialize a Docker swarm.

47. docker swarm join
    # Join a Docker swarm as a worker or manager.

48. docker node ls
    # List nodes in the swarm.

49. docker service ls
    # List services in the swarm.

50. docker system df
    # Show Docker disk usage.

51. docker system prune
    # Remove unused data like stopped containers, networks, etc.

52. docker system events
    # Get real-time events from the Docker server.

53. docker system info
    # Display system-wide information about Docker.

54. docker run --privileged
    # Run a container with extended privileges.

55. docker run --cap-add <capability>
    # Add Linux capabilities to a container.

56. docker run --security-opt <option>
    # Set security options for a container.

57. docker run --network=none
    # Disable networking for a container.

58. docker start --attach <container_id>
    # Start a container and attach STDOUT/STDERR.

59. docker wait <container_id>
    # Block until a container stops.

60. docker attach <container_id>
    # Attach local standard input, output, and error streams to a running container.

61. docker service create <service_name>
    # Create a new service.

62. docker service scale <service_name>=<num_replicas>
    # Scale a service.

63. docker service update <service_name>
    # Update a service.

64. docker build --build-arg <key>=<value> <path>
    # Set build-time variables for Dockerfile.

65. docker build --file <Dockerfile>
    # Specify the Dockerfile name.

# Docker Cleanup
66. docker container prune
    # Remove all stopped containers.

67. docker image prune
    # Remove unused images.

68. docker volume prune
    # Remove unused volumes.

69. docker system prune -a
    # Remove all unused containers, networks, images, and volumes.

# Docker Networking
70. docker network ls
    # List Docker networks.

71. docker network create <network_name>
    # Create a Docker network.

72. docker network inspect <network_name>
    # Inspect a Docker network.

73. docker secret create <secret_name> <file>
    # Create a Docker secret.

74. docker secret ls
    # List Docker secrets.

75. docker secret inspect <secret_name>
    # Display detailed information about a secret.

76. docker swarm init
    # Initialize a swarm.

77. docker swarm join
    # Join a swarm as a worker or manager.

78. docker swarm leave
    # Leave the swarm.

79. docker node ls
    # List nodes in the swarm.

80. docker stack deploy
    # Deploy a stack defined in a Compose or Kubernetes YAML file.

81. docker stack ls
    # List stacks.

82. docker stack ps <stack_name>
    # List tasks in the stack.

83. docker plugin install
    # Install a plugin.

84. docker plugin ls
    # List installed plugins.

85. docker plugin rm <plugin_name>
    # Remove a plugin.

86. docker context ls
    # List Docker contexts.

87. docker context create <context_name>
    # Create a new Docker context.

88. docker context use <context_name>
    # Use a specific Docker context.

89. docker -H <remote_host> <command>
    # Run Docker commands on a remote host.

90. DOCKER_HOST=<remote_host> docker <command>
    # Set the Docker host for a single command.

91. docker config create
    # Create a config from a file or STDIN.

92. docker config ls
    # List Docker configs.

93. docker config inspect
    # Display detailed information about a config.

94. docker import <file>
    # Create an image from a tarball.

95. docker export <container_id>
    # Export a container's filesystem as a tar archive.

96. docker swarm join-token
    # Display the join token for workers or managers.

97. docker swarm init --force-new-cluster
    # Force create a new swarm from scratch.

98. docker swarm update
    # Update the swarm.

99. docker swarm leave --force
    # Force all nodes to leave the swarm.

100. docker swarm ca
     # Manage the root CA used by the swarm.

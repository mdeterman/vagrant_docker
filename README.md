$ vagrant up
Bringing machine 'default' up with 'docker' provider...
==> default: Docker host is required. One will be created if necessary...
    default: Docker host VM is already ready.
==> default: Syncing folders to the host VM...
    default: Rsyncing folder: /Users/mdeterman/git/vagrent_docker/ => /var/lib/docker/docker_1412173263_16149
    default: Rsyncing folder: /Users/mdeterman/git/vagrent_docker/ => /mnt/docker_build_0b1abe78e0ed58dd6661a796eea34990
==> default: Building the container from a Dockerfile...
    default: Image: 7416d811b02b
==> default: Warning: When using a remote Docker host, forwarded ports will NOT be
==> default: immediately available on your machine. They will still be forwarded on
==> default: the remote machine, however, so if you have a way to access the remote
==> default: machine, then you should be able to access those ports there. This is
==> default: not an error, it is only an informational message.
==> default: Creating the container...
    default:   Name: test_test
    default:  Image: 7416d811b02b
    default: Volume: /var/lib/docker/docker_1412173263_16149:/vagrant
    default:   Port: 8008:8080
A Docker command executed by Vagrant didn't complete successfully!
The command run along with the output from the command is shown
below.

Command: "docker" "run" "--name" "test_test" "-d" "-p" "8008:8080" "-v" "/var/lib/docker/docker_1412173263_16149:/vagrant" "7416d811b02b"

Stderr: 2014/09/30 18:57:36 Error response from daemon: No command specified

Stdout:

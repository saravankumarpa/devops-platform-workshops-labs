# This image provides a postgres installation from which to run backups 
FROM registry.access.redhat.com/rhscl/postgresql-10-rhel7

# Set the workdir to be root
WORKDIR /

# Load the backup script into the container (must be executable).
COPY backup-simple.sh /

# Set the default CMD.
CMD sh /backup-simple.sh

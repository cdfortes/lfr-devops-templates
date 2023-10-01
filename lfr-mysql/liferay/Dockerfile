# Use an official Liferay image as parent image
FROM liferay/portal:latest


COPY --chown=liferay:liferay ./deploy /mnt/liferay/deploy


# Copy custom portal configuration to the container
COPY --chown=liferay:liferay ./portal-ext.properties $LIFERAY_HOME/
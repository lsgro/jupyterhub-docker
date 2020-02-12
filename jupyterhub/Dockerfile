FROM jupyterhub/jupyterhub:0.9.3

COPY jupyterhub_config.py .

RUN pip install \
    dockerspawner==0.10.0 \
    jupyterhub-dummyauthenticator
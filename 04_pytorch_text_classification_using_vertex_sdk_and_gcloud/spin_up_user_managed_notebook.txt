gcloud notebooks instances create pytorch-1-9-instance\
    --vm-image-project=deeplearning-platform-release \
    --vm-image-family=pytorch-1-9-cu110-notebooks \
    --machine-type=n1-standard-4 \
    --location=us-west4-a \
    --boot-disk-size=100 \
    --accelerator-core-count=1 \
    --accelerator-type=NVIDIA_TESLA_T4 \
    --install-gpu-driver \
    --network=default

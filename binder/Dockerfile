FROM jupyter/base-notebook

# Install any additional packages if needed
RUN pip install jupyterlab

# Set the command to run JupyterLab with the specified option
CMD ["jupyter", "lab", "--AiExtension.default_language_model=openai-chat:gpt-4"]

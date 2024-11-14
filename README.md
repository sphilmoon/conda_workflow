# Conda Commands for Environment Management

### Latest Update: November 11, 2024 by sphilmoon

---

1. **Creating a New Environment**

    ```bash
    # Create a new Conda environment with the specified name
    conda create --name ENV_NAME
    ```

2. **Activating an Environment**

    ```bash
    # Activate the specified Conda environment
    conda activate ENV_NAME
    ```

3. **Deactivating the Current Environment**

    ```bash
    # Deactivate the currently active environment
    conda deactivate
    ```

4. **Deleting an Environment**

    ```bash
    # Remove a Conda environment completely
    conda remove --name ENV_NAME --all
    ```

5. **Listing All Environments**

    ```bash
    # Show all available Conda environments on your system
    conda env list
    ```

6. **Cloning an Existing Environment**

    ```bash
    # Create an exact copy of an existing environment with a new name
    conda create --name NEW_ENV_NAME --clone EXISTING_ENV_NAME
    ```

---

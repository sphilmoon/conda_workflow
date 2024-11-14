# Conda Commands for Environment Management

### Latest Update: November 11, 2024 by sphilmoon

---

## Managing Conda Environments

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

---

## Viewing and Cloning Environments

1. **Listing All Environments**

    ```bash
    # Show all available Conda environments on your system
    conda env list
    ```

2. **Cloning an Existing Environment**

    ```bash
    # Create an exact copy of an existing environment with a new name
    conda create --name NEW_ENV_NAME --clone EXISTING_ENV_NAME
    ```

---

## My Successful Workflow with Conda

1. **Creating and Activating a New Environment**

    ```bash
    conda create --name MY_ENV
    conda activate MY_ENV
    ```

2. **Viewing and Managing Existing Environments**

    ```bash
    # List all environments
    conda env list

    # Deactivate the environment
    conda deactivate
    ```

3. **Deleting an Environment When No Longer Needed**

    ```bash
    conda remove --name my_env --all
    ```

---

## THE END

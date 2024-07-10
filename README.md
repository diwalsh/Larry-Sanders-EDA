# Larry Sanders: House my Enthusiasm

An EDA project, exploring Seattle's King County Housing Sales data from 2014-2015 to find a client the best home offers under their criteria. 

Client is Larry Sanders.

Larry Sanders' top priority is getting a waterfront property home. <br>
He is working with an upper middle class budget limit. <br>
Larry has 2 Pre-Teen daughters, but does not want to be surrounded by other people's children. He is a germ-o-phobe.<br>
It is also really important to him to be as close as possible to the city's center, to still have urban amenities. 

## Workflow

There are two Jupyter Notebooks.

The first is for data fetching, cleaning and exporting to CSV.<br>
The second is for all EDA exploration and folium mapping. <br>

After all of the plotted graphs and maps are created during the EDA process, a slideslow pdf was created to present to client, Larry Sanders. 

Enjoy! :)

## Requirements

### **`macOS`** type the following commands : 

- `Step_1:` Update Homebrew and install Node by following commands:
    ```sh
    brew update
    brew install node
    ```
- `Step_2:` Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :


- `Step_1:` Update Chocolatey and install Node by following commands:
    ```sh
    choco upgrade chocolatey
    choco install nodejs
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
  
    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

 **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

   ```Bash
   python.exe -m pip install --upgrade pip
   ```

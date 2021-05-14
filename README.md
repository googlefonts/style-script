Style Script is a beautiful upright script with looks that vary from Casual to Formal in appearance. It takes the look and simplicity of 1950s and 60s advertising and combines it with up to date design characteristics.

With three main stylistic sets, Plain, Script and Formal, Style Script transforms the Retro look into a versatile, and powerful font that can be used for nostalgic work, or 21st Century design.

## Building the Fonts

The font is built using fontmake and gftools post processing script. Tools are all python based, so it must be previously installed.

To install all the Python tools into a virtualenv, do the following:

From terminal:

```

cd your/local/project/directory

#once in the project folder create a virtual environment. 
This step has to be done just once, the first time:

python3 -m venv venv

#activate the virtual environment

source venv/bin/activate

#install the required dependencies

pip install -r requirements.txt

```

Then run the this command:

```
cd sources
gftools builder config.yml
```

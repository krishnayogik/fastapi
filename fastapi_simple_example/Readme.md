### simple fast API tutorial

# step 1 Create your virtual environment on you local machine 
`python3 -m venv myenv\n`
use it as source 
`source myenv/bin/activate`


# step 2 You can either run requirements or simply do pip install  of these libraries

`pip install fastapi uvicorn httpie requests httpx`
# step 3 run  your webserver :)

`uvicorn hello:app --reload`

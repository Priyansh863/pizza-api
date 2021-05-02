# pizza-api
#Python 3.7.4 required
1 Steps to run the project
create virtual environment
pip install virtualenv
virtualenv myenv
install all packages by pip install -r requirements.txt
activate virtualenv by myenv/scripts/activate
run project by py manage.py runserver

2 Database 
djongo==1.3.4
mongoengine==0.23.0
Name : rest

3 API
Pizza create (Token is required)
url : http://127.0.0.1:8000/app/PizzaView/
Pizza delete (Token is required)
url : http://127.0.0.1:8000/app/PizzaView/{id}
Pizza update (Token is required)
url : http://127.0.0.1:8000/app/PizzaUpdateView/{id}
Pizza reterive 
url : http://127.0.0.1:8000/app/PizzaView/{id}
Pizza get 
url : http://127.0.0.1:8000/app/PizzaView/
Pizza list filter
http://127.0.0.1:8000/app/PizzaListFilterView/



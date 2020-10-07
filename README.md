URL - http://localhost/dhwani/user or http://localhost/dhwani which redirects to the same.

    Credentials -
        email - superadmin@gmail.com
        password - 123456
        
    API -
      Login -
          # POST 
          # http://localhost/dhwani/api/dhwani_api/login
          # {"email": "superadmin@gmail.com", "password": "123456"}
      
      Get all states -     
          # GET 
	      # http://localhost/dhwani/api/dhwani_api/get_states
      
      Get state  -
          # POST 
          # http://localhost/dhwani/api/dhwani_api/get_state 
          # {"id": "1"}
      
      Get all districts -     
          # GET 
	      # http://localhost/dhwani/api/dhwani_api/get_districts
      
      Get district  -
          # POST 
          # http://localhost/dhwani/api/dhwani_api/get_districts 
          # {"id": "1", "state_id": "1"}
          # {"id": "1", "state_id": ""}
          # {"id": "", "state_id": "1"}
       
       Get all children -     
          # GET 
	      # http://localhost/dhwani/api/dhwani_api/get_child
      
       Get district  -
          # POST 
          # http://localhost/dhwani/api/dhwani_api/get_child
          # {"id": "1", "state_id": "1", "district_id": "1"}
          # {"id": "1", "state_id": "", "district_id": ""}
          # {"id": "", "state_id": "", "district_id": "1"}
          # {"id": "", "state_id": "1", "district_id": ""}
          # {"id": "1", "state_id": "1", "district_id": ""}
          # {"id": "1", "state_id": "", "district_id": "1"}
          # {"id": "", "state_id": "1", "district_id": "1"}


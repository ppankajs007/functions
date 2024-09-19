## functions

  ## PHP 
    # 1. htmlspecialchars(json_encode($doctorList), ENT_QUOTES, 'UTF-8')
        Comment => This function convert php array to js JSON.stringify.
        My usage => I have used this funciton in select dropdown in datatable header label 

 ## JS 
    #1. Array.reduce 
      Comment => I am using this function in create array grouping 
      Ex. => const data = [
              { id: 1, name: 'mango', type: 'fruit' },
              { id: 16, name: 'aa', type: 'veg' },
              { id: 17, name: 'tt', type: 'cold' },
            ];
            
            const groupedData = data.reduce((acc, item) => {
              if (!acc[item.type]) {
                acc[item.type] = [];
              }
              acc[item.type].push(item);
              return acc;
            }, {});
    

      

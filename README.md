# Show_Hide_Any_View_With_Single_Button_Press
This simple code will help to show and hide any type of view on single button press 


`

    @IBAction func selectCategoryButton(_ sender: Any) {
        
        print("button tapped")
        
        //This will show and hide the table view when we press the same button
        if categoriesTableView.isHidden {
            categoriesTableView.isHidden = false
        } else {
            categoriesTableView.isHidden = true
        }
        
 

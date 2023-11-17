# bsp3 File
#   RevitDynamo
    the number indicates which file was done first

    Relevant files : 
    06startpointMakeWallsFromBSP2File.dyn

        Makes 3d walls from the .rvt file
        
        The file takes the data from "walls.xlsx"
        
        " walls.xlsx " is generated by "get_rooms_3.dyn". "get_rooms_3.dyn" generates a new walls.xlsx per floor. This floor must be manually chosen 
        
        The option to change floor is located in the middle of the "get_rooms_3.dyn" file in a dropdown list

    07changeonewall.dyn                    

        Translates a wall from the .rvt file into another wall
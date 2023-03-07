# redux toolkit -notes

# rtk intermediate react v5
            
            install
            import and use 

            slice 
                import 

                define
                    name 
                        initalsate, 
                        reducer(s)
                export, 
                
                import slice in store.js

            use slice 
                dispatch 
                useSelector
            
            redux toolkit query 
                import 

                define 
                    name 
                    basequery
                    endpoints
                
                export 

                import in store.js 
                    middleware

                use 
                    import 
                    use



# redux raw 

    redux 
        install 
        import and use      // store.js 

        reducers            // reducers 
            combineReducers     > parent reducer    > index.js 
                reducer         > tiny reducer      > location.js 

        action creator      // helper function      > generate action type and payload for reducers

        provider            // connect redux with react     > provide state to react 

        use 
            useSelector 
            useDispatch


                
                                
                                
                                
                                
Tiny reducer:    
function (state, action) {
    switch(action.type){
        case: "MUST"
            return 
        default: 
            return 
    }
}
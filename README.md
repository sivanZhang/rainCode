$("#all_checked").click(function(){   
    if(this.checked){   
        $("input.checked").prop("checked", true);  
    }else{   
	$("input.checked").prop("checked", false);
    }   
});

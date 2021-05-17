# react-render-in-array-
react render in array
var arr_of_times = []; 
    var my_results = response.data.result;
    my_results.forEach(element => {
    console.log(element);
    arr_of_times.push(element.cDate);
    });

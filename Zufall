func zufall(_ n : Int, _ min : Int, _ max : Int) -> [Int] {
    var iFeld = [Int]()
    for _ in 1 ... n {
        iFeld.append(Int.random(in: min ... max))
    }
    return iFeld
}

func bubble(_ array : [Int]) -> [Int] {
    var arr = array
    for _ in 0...arr.count {
        for value in 1...arr.count - 1 {
            if arr[value-1] > arr[value] {
                let largerValue = arr[value-1]
                arr[value-1] = arr[value]
                arr[value] = largerValue
            }
        }
    }
    //print("Sorted\(arr)")
    return arr
}

func ausgabe()
{
    let iFeld = [Int](zufall(10,10,15))
    print("Vorher\n",iFeld)
    print(bubble(iFeld))
}

ausgabe()

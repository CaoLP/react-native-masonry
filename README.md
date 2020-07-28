# react-native-masonry

## Getting started

`$ yarn add https://github.com/CaoLP/react-native-masonry.git`

## Usage

```javascript
import  Masonry from 'react-native-masonry';

...
 <Masonry data={[
    {id : 1, uri : "https://via.placeholder.com/150x200"},
    {id : 2, uri : "https://via.placeholder.com/200x200"},
    {id : 3, uri : "https://via.placeholder.com/100x200"}
]}
    containerImageStyle={}
    customRenderItem={({
        data: any;
        uri: string;
        actualSize: {
            width: number;
            height: number;
        };
        column: number;
        width: number;
        height: number;
    })=>{
        return ...
    }}
    refreshColor={"#FFF"}
    canRefresh={false}
    onRefresh={()=>{

    }}
    refreshing={false}
    onEndReach={()=>{

    }}
    columns={2}
    space={2}
    onPress={()=>{

    }}
    renderFooter={()=>{
        return ...
    }}
    renderHeader={()=>{
        return ...
    }}
/>
...

```

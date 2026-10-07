import { StyleSheet, Text, View } from 'react-native'
import React from 'react'

const index = () => {
  return (
    <View style={styles.box}>
      <View style={styles.b1}></View>
      <View style={styles.b2}></View>
      <View style={styles.b3}></View>
      <View style={styles.b4}></View>
      <View style={styles.b5}></View>
    </View>
  )
}

export default index

const styles = StyleSheet.create({
  box:{
    height:"100%",
    width: "100%",
    backgroundColor:'white'
  },
  b1:{
    height: 100,
    width:100,
    backgroundColor:'red',
    margin:20,
    elevation:4
  },
  b2:{
    height:50,
    width: 200,
    backgroundColor:"blue",
    marginLeft: 20,
    opacity:0.6
  },
  b3:{
    height:80,
    width:300,
    backgroundColor:'green',
    marginLeft:20,
    marginTop:20,
    borderWidth:5,
    borderRadius:10,
    borderStyle:'dashed',
    elevation:20,
    shadowColor:'red'

  },
  b4:{
    height: 100,
    width:100,
    backgroundColor:'blue',
    opacity:0.5,
    margin:20,
    elevation:4

  },
  b5:{
    height: 200,
    width:200,
    backgroundColor:'red',
    marginLeft:20,
    elevation:4

  }
})
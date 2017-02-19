/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/* 
 * File:   higherlevelAPI.h
 * Author: huangca9
 *
 * Created on January 23, 2016, 7:15 PM
 */

#ifndef HIGHERLEVELAPI_H
#define HIGHERLEVELAPI_H
#include <string>
using namespace std;
class higherlevelAPI {
public:
    higherlevelAPI();
    higherlevelAPI(const higherlevelAPI& orig);
    higherlevelAPI(unsigned id, string name);
    virtual ~higherlevelAPI();
    getHLID(){return streetID;};
    getHLNM(){return streetSegmentName;};
    setHLID(unsigned a){streetID=a;};
    setHLNM(string a){streetSegmentName=a;};
private:
    unsigned streetID;
    string streetSegmentName;
    
};

#endif /* HIGHERLEVELAPI_H */


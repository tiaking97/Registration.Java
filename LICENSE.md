import java.io.*;
import java.net.*;
import java.util.*;

import com.google.gson.Gson;
import com.google.gson.GsonBuilder;

public class Register {

    public static void main(String[] args)throws IOException {
        //Challenge A: get token                                                
	String regURL= "http://challenge.code2040.org/api/register";
	String json = register.getJson(regUrl, registrationMap());
	Token tokenClass =gson.fromJson(json, Token.class);
	token =	tokenClass.get();
	//Challenge 1:reverse string                                            
	register.reverseString();
	//Challenge 2:find needle                                               
	register.needleIndex();
	//Challenge 3:find non-prefixed words                                   
	register.workPrefixArray();
	//Challenge 4: add interval to date 
	register.getDateStamps();
        //Bonus: checks API challenge status                                    
        register.checkStatus();
        

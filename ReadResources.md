@Service
public class SampleService {
    ...
 
    @Value("classpath:/init/data.json")
    private Resource data;
    ...
}


@Service
public class SampleService {
 
    ...
 
    @Value("classpath:/init/*.json")
    private Resource[] allData;
}

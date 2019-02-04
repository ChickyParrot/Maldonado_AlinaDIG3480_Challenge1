using UnityEngine;
using System.Collections;


public class Rotator : MonoBehaviour
{
    // Start is called before the first frame update
    void Update()
    {
        transform.Rotate(new Vector3(0, 25f, 0) * Time.deltaTime);

    }
}

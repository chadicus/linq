SubjectivePHP\Linq\LinqCollection
===============






* Class name: LinqCollection
* Namespace: SubjectivePHP\Linq
* This class implements: IteratorAggregate, Countable






Methods
-------


### from

    \SubjectivePHP\Linq\LinqCollection SubjectivePHP\Linq\LinqCollection::from(array|\Traversable $collection)

Create a new LinqCollection from the given input.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $collection **array|Traversable** - &lt;p&gt;The items to be linq&#039;d.&lt;/p&gt;



### first

    mixed SubjectivePHP\Linq\LinqCollection::first(callable|null $predicate)

Returns the first element in a sequence that satisfies a specified condition.



* Visibility: **public**


#### Arguments
* $predicate **callable|null** - &lt;p&gt;A function to test each element for a condition.&lt;/p&gt;



### firstOrDefault

    mixed SubjectivePHP\Linq\LinqCollection::firstOrDefault(callable|null $predicate, mixed $defaultValue)

Returns the first element of a sequence, or a default value if no element is found.



* Visibility: **public**


#### Arguments
* $predicate **callable|null** - &lt;p&gt;A function to test each element for a condition.&lt;/p&gt;
* $defaultValue **mixed** - &lt;p&gt;The default value to return.&lt;/p&gt;



### where

    \SubjectivePHP\Linq\LinqCollection SubjectivePHP\Linq\LinqCollection::where(callable $where)

Filters a sequence of values based on a predicate.



* Visibility: **public**


#### Arguments
* $where **callable** - &lt;p&gt;A function to test each source element for a condition&lt;/p&gt;



### skip

    \SubjectivePHP\Linq\LinqCollection SubjectivePHP\Linq\LinqCollection::skip(integer $offset)

Bypasses a specified number of elements in a sequence and then returns the remaining elements



* Visibility: **public**


#### Arguments
* $offset **integer** - &lt;p&gt;The number of elements to skip before returning the remaining elements.&lt;/p&gt;



### take

    \SubjectivePHP\Linq\LinqCollection SubjectivePHP\Linq\LinqCollection::take(integer $count)

Returns a specified number of contiguous elements from the start of a sequence.



* Visibility: **public**


#### Arguments
* $count **integer** - &lt;p&gt;The number of elements to return.&lt;/p&gt;



### count

    integer SubjectivePHP\Linq\LinqCollection::count()

Counts the elements in the sequence.



* Visibility: **public**




### select

    \SubjectivePHP\Linq\LinqCollection SubjectivePHP\Linq\LinqCollection::select(callable $selector)

Projects each element of a sequence into a new form.



* Visibility: **public**


#### Arguments
* $selector **callable** - &lt;p&gt;A transform function to apply to each element.&lt;/p&gt;



### orderBy

    \SubjectivePHP\Linq\LinqCollection SubjectivePHP\Linq\LinqCollection::orderBy(callable $comparer)

Sorts the elements of a sequence in order by using a specified comparer.



* Visibility: **public**


#### Arguments
* $comparer **callable** - &lt;p&gt;A function used to compare each element in the sequence.&lt;/p&gt;



### getIterator

    \Traversable SubjectivePHP\Linq\LinqCollection::getIterator()

Return an external iterator.



* Visibility: **public**



